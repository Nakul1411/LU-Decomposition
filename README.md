# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu
2. Get input from user and print L and U matrix by 'print'.
3. Define a package as "from scipy.linalg import lu_factor,lu_solve" and create the variables as "X" incluprintde the package in that variables .
4. print the variable "X"
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: NAKUL R
RegisterNumber: 212223240102
*/
```
import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: NAKUL R 
RegisterNumber: 212223240102
*/
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
lu_factor,lu_solve
a= np.array(eval(input()))
b= np.array(eval(input()))
lu,piv = lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

## Output:
![lu decomposition]()
![image](https://github.com/Nakul1411/LU-Decomposition/assets/138849780/f8c591ed-ff97-4ad5-9043-0a4b29007609)

![image](https://github.com/Nakul1411/LU-Decomposition/assets/138849780/90e8ad60-964e-419f-8fa7-f5caf23d8c9d)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

