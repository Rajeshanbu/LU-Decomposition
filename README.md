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

![lu 1 decomposition rajesh](https://user-images.githubusercontent.com/118924713/214552946-684386a2-78da-4bd1-8641-a64990d0d580.png)

### 2-lu decomposition

![lu2 decomposition rajesh](https://user-images.githubusercontent.com/118924713/214552994-a43a23a1-8a53-4f73-9815-71845ca58d15.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

