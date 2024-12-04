# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculations
### Step 2: Prepare the lists from each linear equation and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
Developed by:Tharunish vasan.T

Register number:24001333

```
import numpy as np

# Define the matrix
matrix = np.array([
    [4, 2],
    [2, 4]
])

# Compute eigenvalues and eigenvectors
eigenvalues, eigenvectors = np.linalg.eig(matrix)

# Print the results
print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvectors)
```

## Output:![Screenshot 2024-12-04 085004](https://github.com/user-attachments/assets/2560bc68-c59b-446a-875b-38e6c3eec9fe)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
