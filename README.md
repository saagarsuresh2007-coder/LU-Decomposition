# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1. Import the required package.

2.Create the matrix.

3.Find the L and U matrices using LU decomposition.

4.Print the L and U matrices.


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

