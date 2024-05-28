# EX-7: Norm of a matrix
### DATE: 13.04.2024
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
# Register No:2305002023
# Developed By:Sowmiya G

# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

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
![image](https://github.com/RahulM2005R/Norm-of-a-matrix/assets/166299886/355342db-8e0b-4dc9-a059-e529a609134c)
### 2-Norm of a Matrix
![image](https://github.com/RahulM2005R/Norm-of-a-matrix/assets/166299886/360354d6-38dc-495a-822d-e0575dcd5a14)

### Infinity Norm of a Matrix
![image](https://github.com/RahulM2005R/Norm-of-a-matrix/assets/166299886/d3ba1a72-37bc-41a6-b443-9fd80070c805)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
