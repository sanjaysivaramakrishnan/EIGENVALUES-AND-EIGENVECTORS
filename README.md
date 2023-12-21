# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy as np
### Step 2: create a variable and store the inut array
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the value

## Program:
#Program to find the eigen values and eigen vectors.<br>
#Developed by:Sanjay siavramakrishnan M<br>
#RegisterNumber:23013798<br>
<br>
import numpy as np<br>
<br>
x=np.array([[4,2],[2,4]])<br>
eigenvalues,eigenvector=np.linalg.eig(x)<br>
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvector}")<br>

## Output:
![image](https://github.com/sanjaysivaramakrishnan/EIGENVALUES-AND-EIGENVECTORS/assets/151629616/47e1012b-a1ca-427b-a9bb-e8e6db6ef886)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
