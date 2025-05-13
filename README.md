# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
Common Steps for All Norm Calculations

Step 1:
Import the required library (numpy) for matrix operations.

Step 2:
Input the matrix using the np.array() function with eval(input()).

Step 3:
Use the np.linalg.norm() function to calculate the norm of the matrix:
For 1-norm, pass ord=1 as the argument (or directly use np.linalg.norm(matrix, 1)).
For 2-norm, pass ord=2 (or directly use np.linalg.norm(matrix, 2)).
For infinity norm, calculate the maximum row sum using np.max(np.sum(np.abs(matrix), axis=1)).

Step 4:
Format the result to two decimal places using "{:.2f}".format() or f-string.

Step 5:
Print the result.
```
## Program:
```Python
# Register No:
# Developed By:

# 1-Norm of a Matrix


import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat =np.array(eval(input())) 
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans) 
print(norm_of_matrix) 

# Infinity Norm of a Matrix

import numpy as np 
mat =np.array(eval(input())) 
ans=np.linalg.norm(mat,np.inf) 
norm_of_matrix="{:.2f}".format(ans) 
print(norm_of_matrix)  


```
## Output:

### 1-Norm of a Matrix
![Screenshot 2025-05-13 195721](https://github.com/user-attachments/assets/aa220011-da88-4099-b674-3c462e72b3f7)
### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/0ddc8f71-a0a3-4b1f-a8e6-19fdbff2d96b)
### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/5cbf0854-500c-47db-a9b3-f6de2630424b)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
