# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy extension and scipy.linalg extension
2. Initialize the matix values
3. Use lu functions from imported extensions
4. Print the output

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: KARUNIYA M 
RegisterNumber: 212223240068
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: KARUNIYA M
RegisterNumber: 212223240068
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu, piv = lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
(i) To find the L and U matrix
![Screenshot 2024-04-22 223336](https://github.com/karuniya2005/LU-Decomposition/assets/161425769/d7bd3efa-2bfe-4d27-a8b5-c7eb4b2fa71a)

(ii) To find the LU Decomposition of a matrix
![Screenshot 2024-04-22 223348](https://github.com/karuniya2005/LU-Decomposition/assets/161425769/7051960b-7fac-4393-a654-22d8ee738745)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

