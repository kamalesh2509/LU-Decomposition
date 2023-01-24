# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## step 1:
Import numpy library using import statement.
## step 2:
From scipy package import lu().
## step 3:
Get input from user and pass it as an array.
## step 4:
Get P, L, U matrix using lu()
## step 5:
Print L and U matrix

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: E.KAMALESH
RegisterNumber: 22004792
'''
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: E.KAMALESH
RegisterNumber: 22004792
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu,piv),b)
print(x)
*/
```

## Output:
![lu decomposition](Screenshot%20from%202023-01-25%2000-31-52.png)
![](Screenshot%20from%202023-01-25%2000-32-15.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

