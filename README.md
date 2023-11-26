# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
start the program
### Step 2:
Assign np.array() in eigen values and eigen vectors.
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print both the values and vectors,then end the program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: sesank.A
#RegisterNumber:23009543
import numpy as np
a=[2,2],[1,3]
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![image](https://github.com/ALLAMSESANK/EIGENVALUES-AND-EIGENVECTORS/assets/147120920/2b31fa92-e4dc-47cb-b828-e3b15f10ced0)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
