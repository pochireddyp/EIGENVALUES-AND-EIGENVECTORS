# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :  Import NumPy
### Step 2: Define the matrix for which you want to find the eigenvalues and eigenvectors:
python

### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigenvalues and eigenvectors:

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: pochireddy.p
#RegisterNumber:23006090
import numpy as np
a=[[2,2],[1,3]]
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```


## Output:

![Screenshot 2023-12-25 190108](https://github.com/pochireddyp/EIGENVALUES-AND-EIGENVECTORS/assets/150232043/d0ad4253-65ab-486a-ac89-551b896a7060)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
