# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. To start the program.
2. Import the numpy as np.
3. Using the scipy.linag to import lu.
4. Enter the elements of the given matrix.
5. Display the output of the program.

## Program 1:
```
'''Program to find L and U matrix using LU decomposition.

Developed by: NITHISHWAR S

RegisterNumber: 21002766
'''


import numpy as np

from scipy.linalg import lu

#import script

A=np.array(eval(input()))

P,L,U=lu(A)

print(L)

print(U)
```
## Program 2:
```
'''Program to solve a matrix using LU decomposition.

Developed by: NITHISHWAR S 

RegisterNumber: 21002766

'''


import numpy as np

from scipy.linalg import lu_factor,lu_solve

A=np.array(eval(input()))

B=np.array(eval(input()))

lu, pivot= lu_factor(A)

x= lu_solve((lu,pivot),B)

print(x)
```

## Output 1:
![image](https://user-images.githubusercontent.com/94164665/147040143-e203e64d-0d04-4bae-9c62-8bc971de6af0.png)
## Output 2:
![image](https://user-images.githubusercontent.com/94164665/147041625-e3494738-3dce-4e82-8a32-4871c467ccd4.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

