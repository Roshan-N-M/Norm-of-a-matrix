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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
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
<img width="807" height="202" alt="image" src="https://github.com/user-attachments/assets/c1b04ca5-3e94-4c33-b808-946ec3c417bf" />


### 2-Norm of a Matrix
<img width="737" height="257" alt="image" src="https://github.com/user-attachments/assets/6728d0ef-77be-45cd-ba0f-783482849792" />


### Infinity Norm of a Matrix
<img width="747" height="197" alt="image" src="https://github.com/user-attachments/assets/3be1c190-eb31-49a1-b5a5-bf0ef8237677" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
