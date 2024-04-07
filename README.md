# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the NumPy library.
### Step 2: 
Define the matrix as a NumPy array.
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
Print the rank.

## Program:
~~~
#Program to find the rank of a matrix.
#Developed by:MOHAMED HAMEEM SAJITH J 
#RegisterNumber:212223240090
import numpy as np
matrix = np.array([[5, -3, -10],
                   [2, 2, -3],
                   [-3, -1, 5]])

rank = np.linalg.matrix_rank(matrix)
print(f"{rank}")
~~~
## Output:
![image](https://github.com/Sajith7862/RANK-OF-A-MATRIX/assets/145972360/1b4572f1-77d1-4a4c-b2f9-bd2baedbd70a)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

