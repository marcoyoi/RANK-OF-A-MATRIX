# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import numpy as np 
### Step 2: 
Initialize a variable 'A' as an array from the np module 
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
Now print the value
## Program:
```py
#Program to find the rank of a matrix.
#Developed by: Meyyappan.T
#RegisterNumber:23000788
import numpy as np
A=np.array([[3,2,5],[1,1,2],[3,3,6]])
rank = np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![Alt_text](./ex02math.png)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

