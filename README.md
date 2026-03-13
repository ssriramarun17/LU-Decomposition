# LU Decomposition 
Developed by:Sriram arun S
Register number:212225040429

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program 
2. Import the necessary libraries
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. Find the program


## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
Developed by:Sriram arun S
Register number:212225040429
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
Developed by:Sriram arun S
Register number:212225040429
```

## Output:
output1:
<img width="435" height="492" alt="Screenshot 2026-02-24 143812" src="https://github.com/user-attachments/assets/eaec122f-6f4c-4038-9c4e-4842384940c3" />
output2:
<img width="664" height="248" alt="Screenshot 2026-02-24 143914" src="https://github.com/user-attachments/assets/21609c30-064d-4f85-93c2-505ef6492e3a" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

