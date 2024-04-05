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
```Python
# Register No: 212223230107
# Developed By: KRISHNA KUMAR R
# 1-Norm of a Matrix

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:

### 1-Norm of a Matrix
![Screenshot 2024-04-05 220912](https://github.com/Krishna23013541/Norm-of-a-matrix/assets/149557764/6d6ad2b3-ffa3-4bff-9337-6562f9cc66bf)

### 2-Norm of a Matrix
![Screenshot 2024-04-05 220925](https://github.com/Krishna23013541/Norm-of-a-matrix/assets/149557764/cc09d05e-d23e-4e52-8645-0015ffa33dcb)

### Infinity Norm of a Matrix
![Screenshot 2024-04-05 220935](https://github.com/Krishna23013541/Norm-of-a-matrix/assets/149557764/fb2eb70e-2dfe-4e9d-b672-ea0ce09e24f3)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
