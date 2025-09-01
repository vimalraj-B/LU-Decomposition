# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
Step 1:Import the numpy module to use the built-in functions for calculation
Step 2:Prepare the lists from each linear equations and assign in np.array()
Step 3:Using the np.linalg.inv(), we can find the inverse of the given matrix.
Step 4:End the program
```

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: B.VIMALRAJ
RegisterNumber: 212224230304
*/
```
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: B.VIMALRAJ
RegisterNumber: 212224230304
*/
```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```

## Output:
```
L AND U MATRIX:
```
<img width="617" height="632" alt="Screenshot 2025-09-01 094718" src="https://github.com/user-attachments/assets/8ebf0b16-41c2-4349-96fd-15c63527c8f3" />


```
LU DECOMPOSITION:
```

<img width="902" height="738" alt="Screenshot 2025-09-01 094636" src="https://github.com/user-attachments/assets/d1d09f72-aa22-4869-bed3-f15b53178fa9" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

