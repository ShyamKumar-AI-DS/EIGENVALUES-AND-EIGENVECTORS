# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Start the program. 
### Step 2: 
Import numpy.
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program. 

## Program:
~~~
import numpy as np
A = np.array([[4,2],[2,4]])
Value,Vector = np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(Value,Vector))
~~~

## Output:
![github logo](Screenshote.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
