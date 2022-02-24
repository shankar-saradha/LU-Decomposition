# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.import numpy library using import statement.
2.From scipy package import lu().
3.Get input from user and pass it as an array.
4.Get P, L U martix using lu().
5.print L and U matrix.
## Program:
~~~python
import numpy as np
import scipy
from scipy.linalg import lu
A =eval(input())
P,L,U=lu(A)
print(L)
print(U)
~~~

## Output:

![lu(a)](https://user-images.githubusercontent.com/93978702/155523562-1d6f59ec-9de1-4fd3-8f9c-618feb9e6228.jpg)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

