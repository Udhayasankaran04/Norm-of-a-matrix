# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```
Register No: 212222110051
Developed By: M UDHAYA SANKARAN

1-Norm of a Matrix:

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix= "{:.2f}".format(ans)
print(norm_of_matrix)

2-Norm of a Matrix:

import numpy as np
mat= np.array(eval(input()))
ans= np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

Infinity Norm of a Matrix:

import numpy as np
mat= np.array(eval(input()))
ans= np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Udhayasankaran04/Norm-of-a-matrix/assets/119393933/28d4f4c3-f8c0-4415-a85b-83f51aeb470e)

### 2-Norm of a Matrix
![image](https://github.com/Udhayasankaran04/Norm-of-a-matrix/assets/119393933/59668be0-176a-4d67-8064-0cfd45c6e15f)

### Infinity Norm of a Matrix
![image](https://github.com/Udhayasankaran04/Norm-of-a-matrix/assets/119393933/683fa092-7e57-4bbc-8246-3b4c8eab9cea)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
