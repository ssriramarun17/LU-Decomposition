# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5.End the program
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Sriram arun S
RegisterNumber: 212225040429
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Sriram arun S
RegisterNumber: 212225040429
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
*/
```

## Output:
<img width="1217" height="570" alt="Screenshot 2026-03-27 181816" src="https://github.com/user-attachments/assets/f030f507-c7d4-425c-a903-e1bb410f265c" />
<img width="1219" height="767" alt="Screenshot 2026-03-27 181919" src="https://github.com/user-attachments/assets/ffdc2ac8-b2cf-4991-87d0-2eccd034e934" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

