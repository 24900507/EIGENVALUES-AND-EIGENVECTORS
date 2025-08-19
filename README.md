# EIGENVALUES-AND-EIGENVECTORS
## Developed by : AKASH G
## Register Number: 212224100004
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : First, import numpy as np loads the NumPy library so you can use its functions.
### Step 2: The next line creates a 3×3 matrix A using np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Finally, the print() statement displays the eigenvalues and eigenvectors on the screen.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: AKASH G
#RegisterNumber: 212224100004

import numpy as np
A = np.array([[-2, 2, -3],[ 2, 1, -6],[-1,-2,  0]])
eigenvalues,eigenvectors = np.linalg.eig(A)
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
```
## Output:
<img width="1464" height="922" alt="image" src="https://github.com/user-attachments/assets/0de0ce26-719a-48e8-bf4a-ffb132c71779" />
<img width="1447" height="372" alt="image" src="https://github.com/user-attachments/assets/cd9acca1-b7d3-442a-a28f-fc273282ac00" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
