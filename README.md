# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
open your laptop
### Step2
go to lms site
### Step3
do the program and check it
### Step4
then submit it
### Step5
and upload in the github

## Program:
```
Developed by: IBRAHIM FEDAH S
Reference number: 23014264

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("/content/cars (1).csv")
x=df[['Weight','Volume']]
y=df['CO2']
regr=linear_model.LinearRegression()
regr.fit(x,y)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
predictedCO2=regr.predict([[3300,1300]])
print("Predicted CO@ for the corresponding weight and volume",predictedCO2)





```
## Output:
![WhatsApp Image 2024-01-02 at 03 51 58_f7e72a70](https://github.com/ibrahimfedahs/Multivariate-Linear-Regression/assets/150319493/dfb71aa0-5436-46d1-bf32-73f30596ccdb)

### Insert your output

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
