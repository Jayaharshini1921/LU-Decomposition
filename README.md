## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1 Define the package as scipy.linalg import lu.
2 Get input from user and print L and U matrix by 'print' .
3 Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable
4 print the variable 'X'


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: jayaharshini s
RegisterNumber: 212224100024
*/

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: jayaharshini s
RegisterNumber: 212224100024
*/

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,p=lu_factor(a)
x=lu_solve((lu,p), b)
print(x)
```

## Output:
<img width="1252" height="950" alt="Screenshot 2025-09-02 125624" src="https://github.com/user-attachments/assets/40d571a9-2d8d-48b7-ac3b-e58ec7c67b7a" />

<img width="1183" height="881" alt="Screenshot 2025-09-02 125638" src="https://github.com/user-attachments/assets/8c2edaa3-3f3e-45fe-8b5b-67d962177250" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

