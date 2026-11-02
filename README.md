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
# Register No: 212225100002
# Developed By:Amrita B S
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix
<img width="1164" height="694" alt="690879574-87c03c3e-b7cf-46bd-985e-0233e95d9191" src="https://github.com/user-attachments/assets/9c1dd6fe-6feb-454c-9257-528b4ca845bb" />


### 2-Norm of a Matrix
<img width="631" height="627" alt="image" src="https://github.com/user-attachments/assets/579b6d5e-958b-4f7c-8434-79217a3c1e44" />


### Infinity Norm of a Matrix
<img width="1146" height="658" alt="690880512-ed2191db-8138-43b9-963a-94c0eac449f1" src="https://github.com/user-attachments/assets/aa8a890d-3fad-4cb4-b9aa-e69edc5a2864" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
