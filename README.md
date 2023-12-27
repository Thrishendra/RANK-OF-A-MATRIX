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
#Developed by: T Thrishendra
#RegisterNumber:23003501
import numpy as np
a=[[5,-3,-10],[2,-2,-3],[-3,-1,5]]
sol=np.linalg.matrix_rank(a)
print(sol)
```
## Output:
![Screenshot 2023-11-20 185704](https://github.com/Thrishendra/RANK-OF-A-MATRIX/assets/145742464/87f64eaa-06c5-4f0c-8bbb-076da9b4b248)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

