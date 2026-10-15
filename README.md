# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

### Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### 5(a)
### Step 1: Read the input values.
### Step 2: Import the required packages.
### Step 3: Find the lower triangular matrix (L) and upper triangular matrix(U).
### Step 4: Print the output.

### 5(b)
### Step 1: import the required Numpy and Scipy libraries
### Step 2: Define the coefficient matrix (A) and the constant matrix (B)
### Step 3: perform LU Decomposition to split matrix (A) into lower triangular(L) and upper triangular(U) matrices
### Step 4: Solve the equations using L and U matrices
## Program:
(i) To find the L and U matrix


### Program to find L and U matrix using LU decomposition.
### Developed by: GOWTHAM K
### RegisterNumber: 26014578
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### from scipy.linalg import lu
### A=np.array(eval(input()))
### P,L,U = lu(A)
### print(L)
### print(U)

(ii) To find the LU Decomposition of a matrix

### Program to solve a matrix using LU decomposition.
### Developed by : GOWTHAM K
### RegisterNumber: 26014578
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### from scipy.linalg iumport lu_factor,lu_solve
### a=np.array(eval(input()))
### b=np.array(eval(input()))
### l,p=lu_factor(a)
### x=lu_solve((l,p),b)
### print(x)


## Output:
### 5(a)
<img width="1202" height="514" alt="Screenshot 2026-10-15 212116" src="https://github.com/user-attachments/assets/ef982694-1776-4267-9cb9-69bd129389ba" />
<img width="1257" height="485" alt="Screenshot 2026-10-15 212205" src="https://github.com/user-attachments/assets/7441f34c-4956-4437-a3d2-1d0455908fd2" />
 5(b)
<img width="1213" height="519" alt="Screenshot 2026-10-15 213254" src="https://github.com/user-attachments/assets/c0d993b7-3be2-4536-b219-fc99585c7103" />
<img width="1500" height="219" alt="Screenshot 2026-10-15 214741" src="https://github.com/user-attachments/assets/f9ccc34b-d097-4025-b307-1a412e12fc7a" />





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

