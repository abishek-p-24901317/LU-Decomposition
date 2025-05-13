# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import Required Libraries: Import numpy as np for array handling and lu from scipy.linalg for LU decomposition.
2. Input the Matrix: Read the matrix from user input using eval(input()) and convert it to a NumPy array.
3. Perform LU Decomposition: Apply lu(A) to decompose matrix A into three matrices: P (permutation), L (lower triangular), and U (upper triangular).
4. Extract L and U Matrices: Store the lower triangular matrix in L and the upper triangular matrix in U.
5. Display the Result: Print the matrices L and U to show the decomposition results.
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Abishek P
RegisterNumber: 212224240002
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
Developed by: Abishek P
RegisterNumber: 212224240002
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
*/
```

## Output:
##  L and U matrix:
![image](https://github.com/user-attachments/assets/b58f1b8d-4230-46ea-9850-6460a8868009)
## LU decomposition of the matrix:
![image](https://github.com/user-attachments/assets/0720a95c-ba0f-4d4e-9ce4-f9d6aba41e0a)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

