# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : we have imported numpy which is needed.

### Step 2: we have created a matrix using np.array with different values in it.

### Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: finally,print the values of the eigen values and eigen vectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Mohanram Gunasekar
#RegisterNumber: 212223240095
import numpy as np
A=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![Screenshot 2024-05-18 154441](https://github.com/MohanramGunasekar/EIGENVALUES-AND-EIGENVECTORS/assets/139841812/e3c712a3-30c8-4a99-8143-2787b5a2046e)
![Screenshot 2024-05-18 154509](https://github.com/MohanramGunasekar/EIGENVALUES-AND-EIGENVECTORS/assets/139841812/c9f09c5d-2162-4600-afad-702248bb12d8)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
