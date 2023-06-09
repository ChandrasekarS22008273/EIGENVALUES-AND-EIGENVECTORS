# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1 :
import numpy as np

## Step 2:
Get the eigen values

## Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

## Step 4:
print the eigen value and eigen vectors 

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: Chandrasekar S
#RegisterNumber: 212222230025
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are",evalues, "and Eigen Vectors are",evector)


## Output:
![image](https://github.com/ChandrasekarS22008273/EIGENVALUES-AND-EIGENVECTORS/assets/119643845/13a0afc5-f11f-4ece-bbf0-b779a29ff46f)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
