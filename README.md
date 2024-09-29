# Implementation of Univariate Linear Regression
## AIM:
To implement univariate Linear Regression to fit a straight line using least squares.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm:
Step 1: Start

Step 2: Get the independent variable X and dependent variable Y.

Step 3: Calculate the mean of the X -values and the mean of the Y -values.

Step 4: Find the slope m of the line of best fit using the formula. 
<img width="231" alt="image" src="https://user-images.githubusercontent.com/93026020/192078527-b3b5ee3e-992f-46c4-865b-3b7ce4ac54ad.png">

Step 5: Compute the y -intercept of the line by using the formula:
<img width="148" alt="image" src="https://user-images.githubusercontent.com/93026020/192078545-79d70b90-7e9d-4b85-9f8b-9d7548a4c5a4.png">

Step 6: Use the slope m and the y -intercept to form the equation of the line.

Step 7:Obtain the straight line equation Y=mX+b and plot the scatterplot.

Step 8: End 
## Program:
Program to implement univariate Linear Regression to fit a straight line using least squares.
Developed by: Ariya Viniya.G
RegisterNumber:  21223080005
```
/*
import numpy as np
import matplotlib.pyplot as plt
x=np.array(eval(input()))
y=np.array(eval(input()))
xmean=np.mean(x)
ymean=np.mean(y)
num,denum=0,0
for i in range(len(x)):
  num+=(x[i]-xmean)*(y[i]-ymean)
  denum+=(x[i]-xmean)**2
m=num/denum
c=ymean-m*xmean
print(m,c)
y_pred=m*x+c
print(y_pred)
plt.scatter(x,y)
plt.plot(x,y_pred,color='red')
plt.show()
*/
```

## Output:
![Screenshot 2024-08-22 092008](https://github.com/user-attachments/assets/759eff08-6bd7-48ea-b422-3bf7ab081ad0)


## Result:
Thus the univariate Linear Regression was implemented to fit a straight line using least squares using python programming.
