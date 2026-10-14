# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: import reqiured modules
### Step 2: create a maatrix using np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: print the result
## Program:import os

os.environ["OPENBLAS_NUM_THREADS"]= "1"

import numpy as np

A=np.array([[1,2,3],[3,6,9]])

sol=np.linalg.matrix_rank(A)

print(sol)
## Output:<img width="571" height="653" alt="{3121CD98-9662-4FB2-9EEC-D3C825BC7DCA}" src="https://github.com/user-attachments/assets/09e83bd0-3144-41c9-96a6-f9183eef320e" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

