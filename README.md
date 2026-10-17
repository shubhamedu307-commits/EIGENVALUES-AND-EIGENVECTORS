# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:End the program 

## Program:

#Program to find the eigen values and eigen vectors.
#Developed by: SHUBHAM KUMAR
#RegisterNumber:26013866

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([[2, -3, 0], [2, -5, 0], [0, 0, 3]])

values, vectors = np.linalg.eig(A)

print("Eigen values are {} and Eigen Vectors are {}".format(values, vectors))

<img width="870" height="652" alt="Exp-04 - Record Eigen Values and Eigen Vectors" src="https://github.com/user-attachments/assets/da70bf6d-7bde-412d-98ff-3d3518429939" />





## Output:<img width="1087" height="133" alt="Exp-04 - Record Eigen Values and Eigen Vectors result" src="https://github.com/user-attachments/assets/751f631f-7d04-45b9-b126-83e562aee92f" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
