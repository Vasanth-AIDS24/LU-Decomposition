# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy.linalg import lu
3. give inputs in the format of array
4. lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
5. print the output

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

Developed by: Vasanth P
RegisterNumber: 24900136
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
Developed by: Vasanth P
RegisterNumber: 24900136
*/
```

## Output:
![lu decomposition]()![Screenshot from 2024-12-02 20-31-57](https://github.com/user-attachments/assets/93ff1aeb-7611-465c-8290-6ae30d72a46f)
![image](https://github.com/user-attachments/assets/8d94b45b-fada-40a7-a62f-d896d9e69c3d)
![image](https://github.com/user-attachments/assets/1c6df065-9eef-4b80-88a6-9bed6e66b6ed)
![image](https://github.com/user-attachments/assets/2bff05cb-0d1e-4b3a-8aa3-01497e8c39e4)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

