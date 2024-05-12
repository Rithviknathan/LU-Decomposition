# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Using library scipy.linalg,import lu to find l and u matrices and lu_factor,lu_solve to find result
3.Prepare the lists from given matrix 
4. Using lu(),l and u matrices can be printed and using lu_factor() and lu_solve() to find resultant matrix

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: RITHVIK S
RegisterNumber: 212223100045

from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: RITHVIK S
RegisterNumber: 212223100045

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
```
## Output:
![lu decomposition]()
![Screenshot (6)](https://github.com/Rithviknathan/LU-Decomposition/assets/148410509/522215c7-2bb8-4bea-b04f-9ca404049187)
![Screenshot (7)](https://github.com/Rithviknathan/LU-Decomposition/assets/148410509/3bb58710-1c0a-4fc1-b02a-b4d691e1cdac)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

