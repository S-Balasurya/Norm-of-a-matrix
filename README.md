# Norm of a matrix

~~~
Name: Bala Surya S
Register No: 212225100003
~~~

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

# 1-Norm of a Matrix

Write a python program to find the 1-Norm of a matrix and display the results in two decimal places.

~~~
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
~~~

# 2-Norm of a Matrix

Write a program to find L2-norm of a matrix and display the result in two decimal places.

~~~
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
~~~

# Infinity Norm of a Matrix

Write a program to find the Infinity of a matrix and display the result in two decimal places.

~~~
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
~~~

## Output:
### 1-Norm of a Matrix

<img width="594" height="207" alt="1" src="https://github.com/user-attachments/assets/6b6ef3f7-bf99-4fef-adf6-dfef59d4f54d" />


### 2-Norm of a Matrix

<img width="529" height="246" alt="2" src="https://github.com/user-attachments/assets/025f001d-1846-478b-b0c1-69349cff5c85" />


### Infinity Norm of a Matrix

<img width="590" height="203" alt="3" src="https://github.com/user-attachments/assets/76ee2dc4-79de-43cc-ab6f-54893767aad1" />

## Result

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
