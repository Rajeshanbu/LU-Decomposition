# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### 1.import numpy package 
### 2.get the import matrix 
### 3.find the lu decoomposition 
### 4.print the output 

## Program:
```python
(i) To find the L and U matrix
'''Program to find L and U matrix using LU decomposition.
Developed by:Rajesh A 
RegisterNumber:22008551 
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)

(ii) To find the LU Decomposition of a matrix
'''Program to solve a matrix using LU decomposition.
Developed by:Rajesh A
RegisterNumber: 22008551
'''

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,u=lu_factor(a)
x=lu_solve((l,u),b)
print(x)
```

## Output:
### 1-lu decomposition
![output1](lu1.png)

### 2-lu decomposition
![output1](lu2.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

