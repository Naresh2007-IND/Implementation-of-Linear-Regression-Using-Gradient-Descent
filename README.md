# Implementation-of-Linear-Regression-Using-Gradient-Descent

## AIM:
To write a program to predict the profit of a city using the linear regression model with gradient descent.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import necessary libraries (numpy, matplotlib, sklearn.linear_model).
2. Create a LinearRegression model object.
3. Accept user input (x_input) for hours studied.
4. Generate predicted values (Y_pred) for the dataset.

## Program:
```python
/*
Program to implement the linear regression using gradient descent.
Developed by: Naresh J
RegisterNumber:  212225230195
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
data=pd.read_csv("Startup.csv")
X=data['R&D Spend'].values
Y=data['Profit'].values
X=(X-X.mean())/X.std()
m=0
b=0
learning_rate=0.1
epoches=1000
n=len(X)
for i in range(epoches):
    Y_predict=m*X+b
    dm=(-2/n)*np.sum(X(Y-Y_predict))
    db=(-2/n)*np.sum(Y-Y_predict)
    m=m-learning_rate*dm
    b=b-learning_rate*db
print("Slope(m):",m)
print("Intercept(b):",b)
y_predict=m*X+b
plt.scatter(X,Y)
plt.plot(X,Y_predict)
plt.xlabel("R&D Spend (Normalized)")
plt.ylabel("Profit")
plt.title("Gradient Descent on 50_Startups Dataset")
plt.show()
*/
```

## Output:
![linear regression using gradient descent](sam.png)<img width="889" height="519" alt="simple linear regression Ex-03" src="https://github.com/user-attachments/assets/600025cb-32f6-473e-8da7-55391572ad96" />



## Result:
Thus the program to implement the linear regression using gradient descent is written and verified using python programming.
