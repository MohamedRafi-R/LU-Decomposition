# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy.linalg import lu,lu_factor,lu_piv
3. Get input from the user as eval(input())
4. Use lu_factor and lu_solve to find LU decomposition
5. print L,U
6. print x

## Program:
(i) To find the L and U matrix
```
#Program to find L and U matrix using LU decomposition.
#Developed by:R.Mohamed Rafi
#RegisterNumber:212224040195
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
p,l,u=lu(A)
print(l)
print(u) 
```


(ii) To find the LU Decomposition of a matrix
```
#Program to solve a matrix using LU decomposition.
#Developed by: R.Mohamed Rafi
#RegisterNumber: 212224040195
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
l,p=lu_factor(A)
x=lu_solve((l,p),B)
print(x)
```

## Output:
![lu decomposition]()
![Screenshot 2025-04-12 134956](https://github.com/user-attachments/assets/260f3b7e-bbdc-4b69-8148-37a2dc9fe0e8)
![Screenshot 2025-04-12 135004](https://github.com/user-attachments/assets/96a4623e-6a86-4dee-ae41-9c984ca0e6da)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

