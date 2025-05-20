# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm for Finding L and U matrix:
1. Import Required Libraries: Import numpy as np for array handling and lu from scipy.linalg for LU decomposition.
2. Input the Matrix: Read the matrix from user input using eval(input()) and convert it to a NumPy array.
3. Convert the input into a NumPy array.
4. Apply the lu() function to the matrix A to get:P: Permutation matrix, L: Lower triangular matrix, U: Upper triangular matrix
5. Display the Result: Print the matrices L and U
## ALgorithm for LU Decomposition:
6. Start the program.
7. Prompt the user to enter: Matrix A (coefficients of the system).Vector b (constants on the right-hand side).
8. Import necessary libraries: numpy for handling arrays. scipy.linalg.lu_factor and lu_solve for LU-based solving.
9. Convert both inputs (A and b) to NumPy arrays.
10. Use lu_factor(A) to perform LU decomposition: Returns a combined LU matrix. Also returns pivoting info (piv) for row swaps.
11. Use lu_solve((lu, piv), b) to solve the linear equation.This uses the LU factors to compute the solution x.
12. Display the result (solution vector x).

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

