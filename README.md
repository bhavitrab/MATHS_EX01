-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Aim:
To write a python program to find a solution to a system of linear equations.

Equipment’s required:
Hardware – PCs
Anaconda – Python 3.7 Installation / Moodle-Code Runner
Algorithm:
Step 1:
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
Using the np.linalg.solve(), we can find the solutions.

Step 4:
End the program

Program:
```
#Program to find the solution for the given linear equations.
#Developed by BHAVITRA B
#RegisterNumber:: 212225040047
import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
X=np.linalg.solve(A,B)
print(X)
```
Output:
<img width="1272" height="209" alt="Screenshot 2026-02-05 132431" src="https://github.com/user-attachments/assets/f233ebd5-60ce-491c-80bf-4a584a3e6168" />

Result:
Thus the solutions for the linear equations are successfully solved using python program
