# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
Step 1: Import the numpy module to use the built-in functions for calculation
Step 2: Prepare the lists from each linear equations and assign in np.array()
Step 3: Using the np.linalg.solve(), we can find the solutions.
Step 4: End the program
```
## Program:
```
#Developed by: M.Mahalakshmi
#RegisterNumber: 212224230148
```
```
import numpy as np
matrix = np.array([[5, -3, -10],
                   [2, 2, -3],
                   [-3, -1, 5]])
rank = np.linalg.matrix_rank(matrix)
print(rank)
```
## Output:

![Screenshot 2025-03-03 083723](https://github.com/user-attachments/assets/10bda96a-164c-46ce-a2ad-ab21fdb1d460)


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

