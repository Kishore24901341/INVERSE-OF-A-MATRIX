# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
 Import the numpy module to use the built-in function for calculation
### Step 2:
 Prepare the lists from each equations and assign in np.aaray()
### Step 3:
 Using the  np.linalg.solve(),we can find the solutions.
### Step 4 :
END OF PROGRAM

## Program:
import numpy as np

matrix = np.array([[6, 2, 3],
                  [3, 1, 1],
                  [10, 3, 4]])

inverse_matrix = np.linalg.inv(matrix)

print(inverse_matrix)

## Output:
![image](https://github.com/user-attachments/assets/1dcba23a-4236-4ae0-857b-5356061b5ec0)

## Result:
Thus the inverse of given matrix is successfully solved using python program

