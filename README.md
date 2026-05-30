# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy library and read the elements of the matrix.
### Step 2: Store the matrix in a NumPy array and check whether the matrix is square.
### Step 3: Use the numpy.linalg.inv() function to find the inverse of the matrix.
### Step 4: Display the inverse of the given matrix.

## Program:
import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

a = np.array([[ 6,2,3],[3,1,1],[10,3,4]])

B=np.linalg.inv(a)

print(B)
## Output:
<img width="1295" height="365" alt="image" src="https://github.com/user-attachments/assets/0401ad1a-73e2-438a-af18-43807666d004" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

