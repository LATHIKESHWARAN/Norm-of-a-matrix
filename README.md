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
# Register No:LATHIKESHWARAN J	
# Developed By:212222230072
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)



# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)



# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)



```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-10-04 133233](https://github.com/LATHIKESHWARAN/Norm-of-a-matrix/assets/119393556/8b847610-4653-4b3c-92df-161ca154b90c)


### 2-Norm of a Matrix
![Screenshot 2023-10-04 133257](https://github.com/LATHIKESHWARAN/Norm-of-a-matrix/assets/119393556/58e54b89-71ef-41d0-931d-8220ef55ecaa)


### Infinity Norm of a Matrix
![Screenshot 2023-10-04 133321](https://github.com/LATHIKESHWARAN/Norm-of-a-matrix/assets/119393556/fa3c7d44-b517-4921-bf45-1bc3b2fe0f75)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
