##EX NO: 04
##DATE:01.04.24
# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors.
## Equipment’s required:
1. 	Hardware – PCs.
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner.
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array().
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.
## Program:
```
Developed by : Jaikanth B
Register number : 2305002010
import numpy as np
A=np.array([[2,2],[1,3]])
values,vectors = np.linalg.eig(A)
print("The eigenvalues and eigenvectors for the given matrix is\n",values,vectors)
```

## Output:
![image](https://github.com/jaikanth25/EIGENVALUES-AND-EIGENVECTORS/assets/155935294/dfe54f8d-aed3-4117-a23b-55fd23a03d1d)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
