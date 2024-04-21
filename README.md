# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1 :
Import the NumPy library and give it the alias 'np'. NumPy is used for numerical operations, including finding eigenvalues and eigenvectors.
## Step 2:
Create a 3x3 matrix 'A' using a nested list to represent rows.
## Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
## Step 4:
Print the calculated eigenvalues and eigenvectors to the console.
## Step 5:
End the program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SARWESHVARAN A
#RegisterNumber:212223230198
import numpy as np 
matrix=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigenvalues,eigenvectors=np.linalg.eig(matrix)
print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvectors)
```
## Output:
![Eigen value and Eigen vector](<Eigen value and Eigen vector.png>)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
