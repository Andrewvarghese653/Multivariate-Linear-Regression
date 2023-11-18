# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>
import panda



### Step2
<br>
import linear model form sklearn



### Step3
<br>
read the file cars.csv



### Step4
<br>
assign the values for x and y as required

### Step5
<br>
create the linearRegression model and predict the output



## Program:
```python
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1).csv")
x=df[['Weight','Volume']]
y=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(x,y)
print("Coefficient: ",regr.coef_)
print("Intercept:",regr.intercept_)
predictedCO2=regr.predict([[3300,1300]])
print("predicted CO2 for the corresponding weight and volume",predictedCO2)







```
## Output:

<img width="833" alt="Screenshot 2023-11-18 at 11 06 39 AM" src="https://github.com/Andrewvarghese653/Multivariate-Linear-Regression/assets/145822115/176babdb-f594-42fb-aad8-346d7359a72a">


<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
