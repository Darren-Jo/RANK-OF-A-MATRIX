# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the NumPy module to use mathematical and matrix functions.
### Step 2: Create a matrix using np.array() and store it in a variable A.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Print the value of X to display the rank of the matrix.
## Program:
```
#Program to find the rank of a matrix.
#Developed by: K DARREN JOSEPH 
#RegisterNumber: 212225230039
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixa=([[1,2,3],[3,6,9]])
result=np.linalg.matrix_rank(matrixa)
print(result)
```
## Output:
<img width="286" height="160" alt="image" src="https://github.com/user-attachments/assets/82313beb-effa-4137-82b5-4277f76f8fea" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

