# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpr module.
### Step 2: Declare the matrix to a variable.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:  Print the Eigen values and Vectors. And End the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:madhesh v
#RegisterNumber:212225040214

import numpy as np

A = np.array([[-2,  2, -3], [ 2,  1, -6], [-1, -2,  0]])


eigenvalues, eigenvectors = np.linalg.eig(A)


print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")


```
<img width="1260" height="931" alt="image" src="https://github.com/user-attachments/assets/25df190e-96eb-466e-8209-1cb4f72e7279" />

## Output:<img width="1261" height="366" alt="image" src="https://github.com/user-attachments/assets/adc1feed-be0f-441b-b3af-e6ce637dcdcf" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
