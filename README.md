# EX -03-INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the inverse of the given matrix
### Step 4: End the program

## Program:
#Program to find the inverse of a matrix.

#Developed by: KISHORE NARAYANAN S R

#RegisterNumber:212223110023

import numpy as np

A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])

inverse=np.linalg.inv(A)

print(inverse)


## Output:
![Screenshot 2024-04-15 133310](https://github.com/KISHORENARAYANANSR/INVERSE-OF-A-MATRIX/assets/148202102/26de4406-bf09-4af6-8b06-67627da8245d)

## Result:
Thus the inverse of given matrix is successfully solved using python program

