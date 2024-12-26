# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm 1:
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Algorithm 2:
1. Input the Matrix: The code takes the input matrix and the constant vector b from the user, converts them into NumPy arrays.
2. LU Decomposition: The lu_factor function from scipy.linalg performs LU decomposition on the input matrix, decomposing it into lower triangular (L) and upper triangular (U) matrices.
3. Solving th linear sytem of Equations.
4. Output Solution: The calculated solution vector solution is printed to the console.


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: ANTO WILLIAMS S
RegisterNumber: 24901055

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)


(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: ANTO WILLIAMS S 
RegisterNumber: 24901055

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```
```

## Output:

![Screenshot 2024-12-12 204358](https://github.com/user-attachments/assets/d5d7c5b0-81ae-4e4b-ad76-1817cb8d32c1)



![Screenshot 2024-12-12 204818](https://github.com/user-attachments/assets/f7014647-fc6c-464a-a241-d74daa64c241)








## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

