# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation.
### Step 2: 
prepare the listfrom each linear equation and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.
## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by:MANOGARAN s 
#RegisterNumber:23004448
import numpy as np
def eigenvalue_eigenvectors(matrix):
    a=np.array(matrix)
    eigenvalue,eigenvector=np.linalg.eig(a)
    return eigenvalue,eigenvector
matrix=[[2,-3,0],[2,-5,0],[0,0,3]]
eigenvalue,eigenvector=eigenvalue_eigenvectors(matrix)
print("Eigen values are",eigenvalue,"and Eigen Vectors are",eigenvector)
```
## Output:
![output](/eigen.jpg)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
