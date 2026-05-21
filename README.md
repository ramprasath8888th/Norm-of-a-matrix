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
# Register No:212225100011
# Developed By:V.DHIVYA
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
<img width="1258" height="395" alt="image" src="https://github.com/user-attachments/assets/5af19814-7c8b-4edc-be2e-b2dcb5a2a134" />


### 2-Norm of a Matrix
<img width="1254" height="389" alt="image" src="https://github.com/user-attachments/assets/10b43194-f9db-4a56-8e0a-f774af5480e6" />

### Infinity Norm of a Matrix
<img width="1264" height="379" alt="image" src="https://github.com/user-attachments/assets/16d2381f-2d6d-4ccb-a3ab-91f44f412157" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
