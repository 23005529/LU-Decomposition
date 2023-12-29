# LU Decomposition 
NAME : ALIYA SHEEMA 

REFERENCE NUMBER : 23005529

DEPARTMENT : AIDS
## AIM :
To write a program to find the LU Decomposition of a matrix.

## EQUIPMENTS REQUIRED :
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## ALGORITHM :
1. Import the lu function from scipy.linalg for LU decomposition.
2. Convert the input string to a numpy array using the eval() function.
3. Use the lu() function to decompose the matrix A into P,and U.
4. Print the L matrix and U matrix.

## PROGRAM :
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: ALIYA SHEEMA
RegisterNumber: 23005529
*/
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
Developed by: ALIYA SHEEMA
RegisterNumber: 23005529 
*/
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## OUTPUT :
(i) To find the L and U matrix

![Alt text](<Output 2.png>)

(ii) To find the LU Decomposition of a matrix

![Alt text](<OUTPUT 1.png>)


## RESULT :
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

