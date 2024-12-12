# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

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

*/
```
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
*/
```

## Output:
![lu decomposition]()![Screenshot 2024-12-12 204358](https://github.com/user-attachments/assets/bbb8eee0-5401-4829-a10f-2c1c8bb34b42)

![Screenshot 2024-12-12 204818](https://github.com/user-attachments/assets/ef1d67a8-7bfe-4bdf-a131-08fdb5811c52)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

