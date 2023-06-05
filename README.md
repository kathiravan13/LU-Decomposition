# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Read the elements of augmented matrix into arrays a and b.
2.Calculate elements of L and U.
3.Print elements of L and U.
4.Find V by solving LV = B by forward substitution.
5.Find X by solving UX = V by backward substitution. 
6.Print Array X as the solution.

## Program:
(i) To find the L and U matrix
```
/*
 

'''Program to find L and U matrix using LU decomposition.
Developed by:kathiravan 
RegisterNumber: 212222230063
'''
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: 
RegisterNumber: 
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3,2,7],[2,3,1],[3,4,1]])
B=np.array([4,5,7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)
*/
```
## Output
![2023-06-05 (1)](https://github.com/kathiravan13/LU-Decomposition/assets/119831303/ec06f2d2-81cf-4afd-b551-6e29c4dc4a5a)

![2023-06-05](https://github.com/kathiravan13/LU-Decomposition/assets/119831303/ec17606a-b758-4685-8a29-ed20ebaa4240)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

