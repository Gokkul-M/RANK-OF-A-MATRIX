# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the built-in functions for calculation
### Step 2:
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Gokkul M
#RegisterNumber:23014201
import numpy as np
A=np.array([[3,2,5],[1,1,1],[3,3,6]])
X=np.linalg.matrix_rank(A)
print(X)
```
## Output:
![image](https://github.com/Gokkul-M/RANK-OF-A-MATRIX/assets/144870543/bf1e27a8-7e48-4f74-b0d9-9a394b21f840)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

