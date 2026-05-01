# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step1 : Characteristic equation (exact method)

### Step 2: Power iteration (largest eigenvalue)

### Step 3: Inverse iteration (smallest eigenvalue)

### Step 4: QR method (efficient for computation)

## Program:
```python

#Program to find the eigen values and eigen vectors.
#Developed by: Siddharth CM
#RegisterNumber:212225040413
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[4,2],[2,4]])
i,e=np.linalg.eig(a)
print(f"Eigen values are {i} and Eigen Vectors are {e}")

```
## Output:
![alt text](image.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
