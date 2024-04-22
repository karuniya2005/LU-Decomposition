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

![Screenshot 2024-04-22 223336](https://github.com/AkilaMohan/LU-Decomposition/assets/161425769/b0ec6be7-b147-4227-bf68-9f372a0e3676)

(ii) To find the LU Decomposition of a matrix

![Screenshot 2024-04-22 223348](https://github.com/AkilaMohan/LU-Decomposition/assets/161425769/9638b6ce-5e8f-47de-825b-728179b3b756)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

