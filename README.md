# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
Start the program
2. Using library scipy.linalg,import lu to find l and u matrices and lu_factor,lu_solve to find result
3. Prepare the lists from given matrix
4. Using lu(),l and u matrices can be printed and using lu_factor() and lu_solve() to find resultant matrix

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:Kathir anand.S
RegisterNumber:23013711 
'''
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
'''Program to solve a matrix using LU decomposition.
Developed by:kathir anand.S
RegisterNumber: 23013711
'''
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
```

## Output:
### (i)

![Screenshot 2023-12-19 093900](https://github.com/Skathiranand/LU-Decomposition/assets/147141136/083e9bc8-df74-44ce-99bf-a8b9a78c223d)

### (ii)

![Screenshot 2023-12-19 093936](https://github.com/Skathiranand/LU-Decomposition/assets/147141136/ef49ee18-7cdd-4422-a2ed-2db5ac7f74fd)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

