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
# Register No:25010248
# Developed By:YASWANTH V
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array(eval(input()))

norm = np.linalg.norm(A, 1)

print("{:.2f}".format(norm))



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array(eval(input()))

norm = np.linalg.norm(A, 2)

print("{:.2f}".format(norm))



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array(eval(input()))

norm = np.linalg.norm(A, np.inf)

print("{:.2f}".format(norm))




```
## Output:
### 1-Norm of a Matrix
<img width="1496" height="820" alt="image" src="https://github.com/user-attachments/assets/8c0d6b03-4563-4f27-89c7-d62651172bc7" />

### 2-Norm of a Matrix
<img width="1203" height="866" alt="image" src="https://github.com/user-attachments/assets/5dca2992-8002-478b-bf56-7da8e286b63b" />

### Infinity Norm of a Matrix
<img width="1738" height="831" alt="image" src="https://github.com/user-attachments/assets/e2cca951-df21-49aa-aecf-fddffbfaceaf" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
