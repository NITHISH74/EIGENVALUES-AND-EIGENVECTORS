# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : start a program.
### Step 2: import a numpy as py.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigen value and vector.

## Program:
import numpy as np 

A=np.array([[4,2],[2,4]])

values,vectors=np.linalg.eig(A) 

print('Eigen values are',values,'and Eigen Vectors are',vectors)

## Output:
![image](https://user-images.githubusercontent.com/94164665/143820096-95a44dce-ad30-4520-b4fe-5aeb1a517c97.png)

![image](https://user-images.githubusercontent.com/94164665/143820058-b7e404d8-79be-44d6-93e2-b713af1601ab.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
