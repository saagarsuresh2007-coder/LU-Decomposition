# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

1. Import the required package.
2. Create the matrix.
3. Find the L and U matrices using LU decomposition.
4. Print the L and U matrices.


## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
/*
Program to find the L and U matrix.
Developed by: Saagar S
RegisterNumber: 212225040351
*/
```
(ii) To find the LU Decomposition of a matrix

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Ashwin Kumar .M
RegisterNumber: 212225040033
*/
```

## Output:
<img width="928" height="227" alt="image" src="https://github.com/user-attachments/assets/a45bc939-6cc3-4c29-85f4-daafd64f9ebf" />
<img width="932" height="168" alt="image" src="https://github.com/user-attachments/assets/55025534-150c-4a05-9646-399c4d550314" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

