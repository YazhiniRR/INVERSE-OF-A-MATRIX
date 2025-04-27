# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Write the matrix A next to an identity matrix of the same size and Perform row operations.
### Step 2: Find the determinant of matrix A and cofactor of each element.
### Step 3: Transpose the cofactor matrix to get the adjoint matrix. The result is the inverse.
### Step 4: Apply LU Decomposition Method.

## Program:
```
import numpy as np
A=np.array([[6,2,3],[3,1,1],[10,3,4]])
result=np.linalg.inv(A)
print(result)
```
## Output:
![Screenshot 2025-04-27 155555](https://github.com/user-attachments/assets/6021525a-b0bd-442a-872c-a378d1db0826)

## Result:
Thus the inverse of given matrix is successfully solved using python program

