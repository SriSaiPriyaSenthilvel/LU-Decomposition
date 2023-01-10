# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SRI SAI PRIYA.S
RegisterNumber: 22006141
import numpy as np
from scipy.linalg import lu 
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SRI SAI PRIYA.S
RegisterNumber: 22006141
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
*/
```

## Output:
(i)![lu decomposition](/Screenshot%20from%202023-01-10%2015-46-54.png)
(ii)
![OUTPUT](/Screenshot%20from%202023-01-10%2015-48-09.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

