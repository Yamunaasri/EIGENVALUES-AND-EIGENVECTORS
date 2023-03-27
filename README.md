# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as np
### Step 2: 
Enter the matrix
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the result and end the program
## Program:
```
#Developed by: T.S.Yamunaasri
#RegisterNumber: 212222240117
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
x,y=np.linalg.eig(A)
print("Eigen values are",x,"and Eigen Vectors are",y)
```
## Output:
![Screenshot 2023-03-27 200047](https://user-images.githubusercontent.com/115707860/227971099-71cb0eef-5f78-4eb6-8535-7c0b6ae23b25.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
