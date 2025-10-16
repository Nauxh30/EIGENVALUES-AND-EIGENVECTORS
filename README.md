# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Start the Python program and Import the NumPy library as np.
### Step 2: 
Create a square matrix (for example, a 2×2 or 3×3 matrix) and store it in a variable.

### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Display both the eigenvalues and eigenvectors as output.

## Program:
```python
import numpy as np


A = np.array([[4, 2],
              [2, 4]])


eigenvalues, eigenvectors = np.linalg.eig(A)

print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")
```

## Output:
<img width="1217" height="281" alt="image" src="https://github.com/user-attachments/assets/c6d02270-629c-4963-9a23-cdbe529f41b1" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
