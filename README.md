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
#Program to find the solution for the given linear equations.
#Developed by: G.SANTHIYA 
#RegisterNumber:212225230218
import numpy as np
a=np.array([[1,3],[2,5]])
b=np.array([5,-3])
x=np.linalg.solve(a,b)
print(x)
```
## Output:
<img width="1495" height="708" alt="Screenshot 2026-02-05 083512" src="https://github.com/user-attachments/assets/6b3535b4-a24b-44a6-8ad8-85be9eddad90" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

