# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

Algorithm
I
Read the matrix from the user.
Initialize lower triangular matrix L and upper triangular matrix U.
Compute the elements of U matrix.
Compute the elements of L matrix.
Display the matrices L and U.
Verify that A = LU.

II
Import the NumPy library and define the matrix A.
Initialize the lower triangular matrix L and upper triangular matrix U with zeros.
Compute the elements of U row by row.
Compute the elements of L column by column and set the diagonal elements of L to 1.
Display matrices L and U, and verify that A=LU.


## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by:  Saagar s
RegisterNumber:  212225040351
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:  Saagar s
RegisterNumber:  212225040351
import numpy as np
from scipy.linalg import lu_factor, lu_solve

A = np.array(eval(input()))
b = np.array(eval(input()))

lu, piv = lu_factor(A)

X = lu_solve((lu, piv), b)

print(X)
*/
```

## Output:
<img width="1331" height="560" alt="image" src="https://github.com/user-attachments/assets/43ca858b-c242-460b-8a65-e15cfe072286" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

