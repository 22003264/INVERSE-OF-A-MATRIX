# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
import the numpy module to use the bulit- in functions for calculation

Step 2:
prepare the list from each inverse of matrix and assign in np.array()

Step 3:
using the np.linalg.matrix_rank() ,we can find the rank of the given matrix

Step 4:
End the program
## Program:
~~~
Developed by:sirisha 
#RegisterNumber:22003264
import numpy as np
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
inverse=np.linalg.inv(A)
print(inverse)
~~~
## Output:
![Screenshot (11)](https://user-images.githubusercontent.com/119389139/211531992-3030656b-8264-4735-9e5e-fefe0ff0f848.png)

## Result:
Thus the inverse of given matrix is successfully solved using python program

