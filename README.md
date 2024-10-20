# DATE :
# EXP 5 : LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X' 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:SREE NIVEDITAA SARAVANAN 
RegisterNumber:212223230213 
*/
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
Developed by: SREE NIVEDITAA SARAVANAN
RegisterNumber:212223230213 
*/
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
```

## Output:

![Screenshot 2024-10-20 200535](https://github.com/user-attachments/assets/10df2c19-bea0-4151-b6f5-0f4069d87916)
![Screenshot 2024-10-20 200556](https://github.com/user-attachments/assets/d0663993-6635-435a-9570-58d139bd5885)
![Screenshot 2024-10-20 200604](https://github.com/user-attachments/assets/066642b8-27b2-40a8-81d3-ef736f270560)
![Screenshot 2024-10-20 200622](https://github.com/user-attachments/assets/3b0f0705-b0d8-4239-a289-c07507fefc1a)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

