# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1: get the input from user
## Step 2: import math and initialise the two values
## Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue andsecond is eigenvector) of the given matrix.
## Step 4:print the values in format

## Program:
```
import numpy as np


A = np.array([[-2, 2, -3],
              [2, 1, -6],
              [-1, -2, 0]])


eigenvalues, eigenvectors = np.linalg.eig(A)


print("Eigen values are", eigenvalues,"and Eigen Vectors are",eigenvectors)

```
## Output:
![Screenshot 2025-03-27 224343](https://github.com/user-attachments/assets/c3790a9c-455b-440a-91b4-2149e92b9080)


# Developed by: Gokul S

# RegisterNumber:212224240044

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
