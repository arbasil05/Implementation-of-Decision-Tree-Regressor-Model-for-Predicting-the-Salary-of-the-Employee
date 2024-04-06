# Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee

## AIM:
To write a program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```
import pandas as pd
data = pd.read_csv("D:/introduction to ML/jupyter notebooks/mama/Salary.csv")
data.head()
```
### Output:
![image](https://github.com/arbasil05/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/144218037/6919eca6-d510-49bb-9881-5fe5d3d504b5)
```
data.info()
```
### Output:
![image](https://github.com/arbasil05/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/144218037/eddd0d7f-744f-431c-8d35-03917e9ee404)
```
data.isnull().sum()
```
### Output:
![image](https://github.com/arbasil05/Implementation-of-Decision-Tree-Regressor-Model-for-Predicting-the-Salary-of-the-Employee/assets/144218037/d9717383-87aa-45f9-b34e-9c8787f7667f)
```
from sklearn.preprocessing import LabelEncoder
le = LabelEncoder()
data['Position'] = le.fit_transform(data['Position'])
data.head()
```



```
/*
Program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee.
Developed by: 
RegisterNumber:  
*/
```

## Output:
![Decision Tree Regressor Model for Predicting the Salary of the Employee](sam.png)


## Result:
Thus the program to implement the Decision Tree Regressor Model for Predicting the Salary of the Employee is written and verified using python programming.
