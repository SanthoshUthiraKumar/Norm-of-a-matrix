# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required:
1.Hardware – PCs
2.Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step 1:
Get the input matrix using np.array()  

### Step 2:
Find the 1-norm,2-norm and infinity norm of the matrix using np.linalg.norm()

### Step 3:
Print the norm of the matrix in two decimal places.

### Step 4:
End the program.

## Program:
```
# Python program to find the 1-norm, 2-norm and infinity norm of the matrix
# Register No: 22009224
# Developed By: Santhosh U

# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```

## Output:
### 1-Norm of a Matrix
![1Norm](https://user-images.githubusercontent.com/119477975/214633955-d413b8d3-b305-4735-ba93-f365895c77f0.png)

### 2-Norm of a Matrix
![2Norm](https://user-images.githubusercontent.com/119477975/214634040-bf6845d4-0a81-4f35-9425-1ace3c2eea05.png)

### Infinity Norm of a Matrix
![InfinityNorm](https://user-images.githubusercontent.com/119477975/214634118-8cc0f5ec-2b94-4a6c-a021-5471a7d11d1d.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
