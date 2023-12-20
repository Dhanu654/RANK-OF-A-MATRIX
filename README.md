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
End Program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: DHANUSYA K
#RegisterNumber: 23006651
import numpy as np
matrix = np.array([[3,2,5],[1,1,2],[3,3,6]])
rank=np.linalg.matrix_rank(matrix)
print(rank)
```
## Output:
![image](https://github.com/Dhanu654/RANK-OF-A-MATRIX/assets/148514965/a0bcebc9-e8ba-4648-a2da-14b5e1e2713d)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

