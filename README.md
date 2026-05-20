# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the `numpy` library to handle matrix operations and `os` to manage environment variables if needed.
### Step 2: Define the given matrix using the `np.array()` function.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Print or store the result to verify the rank.
## Program:
```
Program to find the rank of a matrix.
Developed by: bharath s
RegisterNumber:212225230031
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array( [[5,-3,-10],[2,2,-3],[-3,-1,5]])
solution=np.linalg.matrix_rank(a)
```

## Output:
<img width="1304" height="192" alt="image" src="https://github.com/user-attachments/assets/12e8db56-4f67-408c-a56a-161ed37c0616" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

