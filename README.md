# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: start a program.
### Step 2: import a numpy as py.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print a eigen value and vectors.

## Program:
import numpy as np 

A=np.array([[4,2],[2,4]])

values,vectors=np.linalg.eig(A) 

print('Eigen values are',values,'and Eigen Vectors are',vectors)

## Output:
![image](https://user-images.githubusercontent.com/94164665/143820977-36e08f45-ade7-4fe4-9f97-ff98f7ea165b.png)

![image](https://user-images.githubusercontent.com/94164665/143820962-bb5467ba-3890-45c0-bf83-90b23dd2c613.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
