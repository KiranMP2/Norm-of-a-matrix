# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm 1-Norm of a matrix:
	1. Get the input matrix using np.array()   
    2. Find the 1-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in one decimal places.

## Algorithm 2-Norm of a matrix:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.

## Algorithm Infinity Norm of a Matrix
	1. Get the input matrix using np.array()   
    2. Find the Infinity Norm using np.linalg.norm(matrix, np.inf)
	3. Print the Norm to Two Decimal Places
## Program:
```Python
# Register No:212224230123
# Developed By:KIRAN MP

# 1-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)



# 2-Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print(f"{result:.2f}")



# Infinity Norm of a Matrix
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print(result)




```
## Output:
### 1-Norm of a Matrix
![NORM-1](Screenshot%202025-05-08%20102303.png)

### 2-Norm of a Matrix
![NORM-2](Screenshot%202025-05-08%20102324.png)

### Infinity Norm of a Matrix
![INFINITY-NORM](Screenshot%202025-05-08%20102342.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
