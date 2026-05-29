# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A = np.array([[1,-3],[3,1]])
B = np.array([0,10])
X = np.linalg.solve(A,B)
print(X)
```
<img width="1494" height="440" alt="Screenshot 2026-05-29 141912" src="https://github.com/user-attachments/assets/6fbcce5f-316b-42c1-b022-ce8e8ec24d4b" />

## Output:
<img width="1393" height="271" alt="{6AEEA7FB-FFA2-4D73-BB22-59A6C64D69EB}" src="https://github.com/user-attachments/assets/e69952c6-e69a-40e9-bd4b-733dba224cbe" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

