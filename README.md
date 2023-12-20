# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import numpy module to use the built in function for calculation.
### Step 2: 
Prepare a list for each linear equation and assign in np.array() and assign the coefficient value in the list of each variable.
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: Selva Ganesh R
#RegisterNumber: 23012861
import numpy as np
A= np.array([[1,3],[2,5]])
B= np.array([5,-3])
result= np.linalg.solve(A,B)
print(result)
```
## Output:
![Screenshot 2023-12-20 114950](https://github.com/GANESH23012861/RANK-OF-A-MATRIX/assets/147139861/05fac494-5291-4fdc-af8f-41df867d440a)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

