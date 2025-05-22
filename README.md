# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import Libraries and Load Data

### Step2
Select Features and Target Variable

### Step3
Create and Train the Model

### Step4
Display Model Coefficients and Intercept

### Step5
Make Predictions Using the Trained Model


## Program:
```
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("car (1).csv")
x=df[["Volume","Weight"]]
y=df[["CO2"]]
regression=linear_model.LinearRegression()
regression.fit(x,y)
print(regression.coef_)
print(regression.intercept_)
print(regression.predict([[3300,1300]]))

```
## Output:
![alt text](<Screenshot 2025-05-22 142737.png>)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.