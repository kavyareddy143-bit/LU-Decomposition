# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program
2.Import the necessary libraries(numpy,scipy.linalg)
3.Define the matrix using numpy
4.Use lu(),lu_solve(),lu_factor() to get the solutions
5.End the program
 

## Program:
(i) To find the L and U matrix
```
/*
Program to find L and U matrix using LU decomposition.
Developed by: Annapureddy kavya
RegisterNumber: 212225240011

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
matrix =np.array(eval(input( )))
P,L,U=lu(matrix)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to solve a matrix using LU decomposition.
Developed by: Annapureddy kavya
RegisterNumber: 212225240011

import os
os.environ["OPENBLAS_NUM_THREADS"]="1" 
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
constant=np.array(eval(input()))
piv,lu=lu_factor(matrix)
result=lu_solve((piv,lu),constant)
print(result) 
*/
```

## Output:
<img width="991" height="872" alt="image" src="https://github.com/user-attachments/assets/adc30220-62d3-452f-97f5-f00cf5334d2b" />
<img width="1347" height="605" alt="image" src="https://github.com/user-attachments/assets/dc091596-0001-4b10-a4d4-2a6127d1e873" />
<img width="973" height="832" alt="image" src="https://github.com/user-attachments/assets/0a83e735-7e9d-4d11-8b4f-0340e6263e1b" />
<img width="1151" height="468" alt="image" src="https://github.com/user-attachments/assets/0a33edae-6ddf-4245-822a-1e221ce40c69" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

