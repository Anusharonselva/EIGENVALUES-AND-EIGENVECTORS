# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : To find inverse of a matrix using python programming
### Step 2:  Import numpy as np
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print result

## Program:

import numpy as np

a = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])

values,vectors = np.linalg.eig(a)

print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

## Output:

![Screenshot (77)](https://github.com/Anusharonselva/EIGENVALUES-AND-EIGENVECTORS/assets/119405600/30acaf40-9b27-46ea-9663-f21368815dae)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
