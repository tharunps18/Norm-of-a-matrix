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
# Register No:212224110055
# Developed By: THARUN P S
# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix


import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix


import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)


```
## Output:

### 1-Norm of a Matrix
![Screenshot 2025-05-13 161139](https://github.com/user-attachments/assets/5a92632f-ae70-4b48-a5ee-fbb7d09a4b2c)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/148e4916-838d-464d-affd-593a708ee6ce)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/4b2d894a-1057-4896-a5ab-fab18eb1322b)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
