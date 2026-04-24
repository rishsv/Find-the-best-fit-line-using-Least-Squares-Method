# Implementation of Univariate Linear Regression
## AIM:
To implement univariate Linear Regression to fit a straight line using least squares.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Get the independent variable X and dependent variable Y.
2. Calculate the mean of the X -values and the mean of the Y -values.
3. Find the slope m of the line of best fit using the formula. 
<img width="231" alt="image" src="https://user-images.githubusercontent.com/93026020/192078527-b3b5ee3e-992f-46c4-865b-3b7ce4ac54ad.png">
4. Compute the y -intercept of the line by using the formula:
<img width="148" alt="image" src="https://user-images.githubusercontent.com/93026020/192078545-79d70b90-7e9d-4b85-9f8b-9d7548a4c5a4.png">
5. Use the slope m and the y -intercept to form the equation of the line.
6. Obtain the straight line equation Y=mX+b and plot the scatterplot.

## Program:
```
/*
Program to implement univariate Linear Regression to fit a straight line using least squares.

import matplotlib.pyplot as plt
import numpy as np
x = np.array(eval(input()))
y = np.array(eval(input()))
xmean = np.mean(x)
ymean = np.mean(y)
num, den = 0, 0
for i in range(len(x)):
  num += (x[i] - xmean)*(y[i] - ymean)
  den += (x[i] - xmean)**2
m = num/den
c = ymean-m*xmean
print(m, c)
ypred = m*x+c
print(ypred)
plt.scatter(x,y)
plt.plot(x,ypred, color="y")
plt.show()

Developed by: Rishwanth S V
RegisterNumber: 212225040338
*/
```

## Output:
<img width="1152" height="569" alt="{5ED1C791-6428-4BB7-A22E-5C5EB150BE17}" src="https://github.com/user-attachments/assets/f8c51bca-2629-4edf-bb14-c6168584c066" />
<img width="1151" height="538" alt="{79917F6C-0ADA-4F0D-9EFA-3F463F27A3AF}" src="https://github.com/user-attachments/assets/3de9141e-32b0-4863-aeb6-3700bba6c38c" />

## Result:
Thus the univariate Linear Regression was implemented to fit a straight line using least squares using python programming.
