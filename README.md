# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library using import statement.
2. From scipy package import lu().
3. Get input from user and pass it as an array.
4. Get P, L, U matrix using lu()

## Program:

     #Program to find L and U matrix using LU decomposition.
     #Developed by: Dhiyaneshwar P
     #RegisterNumber: 212222110009
     import numpy as np
     from scipy.linalg import lu
     A=np.array(eval(input()))
     P,L,U=lu(A)
     print(L)
     print(U)

## Output:
![image](https://github.com/Dhiyanesh24/LU-Decomposition/assets/118362288/20181e51-2f41-4ed7-9f52-1884fc87a715)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

