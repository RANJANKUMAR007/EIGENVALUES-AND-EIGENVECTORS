# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : create program by importing numpy library in python
### Step 2: in that create array as list and feed nubers for matrix to perform
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: call the inbuilt fuctions and print result

## Program:
```
Developed by:Ranjan Kumar.G
reg no:212223240138

import numpy as np
A=[[2,-3,0],[2,-5,0],[0,0,3]]
Eigenvalues,Eigenvectors=np.linalg.eig(A)
print("Eigen values are",Eigenvalues,"and Eigen Vectors are",Eigenvectors)

```

## Output:
![alt text](<Screenshot 2024-04-10 203026.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
