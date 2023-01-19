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
	4.End program.
## Program:
```Python
# Register No: Naveen M
# Developed By: 22000748
# 1-Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,1)

norm_of_matrix="{:.2f}".format(ans)

print(norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np

a=np.array(eval(input()))

ans=np.linalg.norm(a,2)

print("{:.2f}".format(ans))


# Infinity Norm of a Matrix


import numpy as np

a=np.array(eval(input()))

ans=np.linalg.norm(a,np.inf)

print("{:.2f}".format(ans))

```
## Output:
### 1-Norm of a Matrix

![norm1](https://user-images.githubusercontent.com/117974950/213455711-d95802ac-c6c1-46e4-a253-e94005a8119e.png)

### 2-Norm of a Matrix

![norn](https://user-images.githubusercontent.com/117974950/213455832-90ba78c2-3548-44e3-9f23-89a6ae4cb54e.png)

### Infinity Norm of a Matrix

![norm3](https://user-images.githubusercontent.com/117974950/213455911-f88dddea-28da-4387-8a43-77688431bdce.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
