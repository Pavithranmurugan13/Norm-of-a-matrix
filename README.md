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
# Register No:212223240112
# Developed By:PAVITHRAN MJ
# 1-Norm of a Matrix
import numpy as np 
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}" . format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:PAVITHRAN MJ
RegisterNumber: 212223240112
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}" . format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix

# Register No:212223240112
# Developed By:PAVITHRAN MJ
#Infinity norm of a matrix 
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
norm_of_matrix = "{:.2f}" . format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-04-23 112157](https://github.com/Pavithranmurugan13/Norm-of-a-matrix/assets/163802201/2a2edd94-e9ca-47cc-b5c2-6a3ad3b99848)

### 2-Norm of a Matrix

![Screenshot 2024-04-23 112211](https://github.com/Pavithranmurugan13/Norm-of-a-matrix/assets/163802201/dc5d60c4-9634-45b5-91ce-3d5212ac73ee)

### Infinity Norm of a Matrix
![Screenshot 2024-04-23 112223](https://github.com/Pavithranmurugan13/Norm-of-a-matrix/assets/163802201/2f939e4f-1b3a-45ee-9141-0a324bd344a2)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
