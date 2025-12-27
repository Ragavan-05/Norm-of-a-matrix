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
a=np.array(eval(input()))
print(f"{np.linalg.norm(a,1):2f}")

# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
print(f"{np.linalg.norm(a,2):.2f}")

# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
print(f"{np.linalg.norm(a,np.inf):2f}")

```
## Output:
<img width="1498" height="867" alt="Screenshot 2025-12-27 175202" src="https://github.com/user-attachments/assets/64160469-fa08-4dee-8969-adbf993c98e8" />
<img width="1432" height="875" alt="Screenshot 2025-12-27 175213" src="https://github.com/user-attachments/assets/9e2b024c-13d2-4e00-ad8d-d30ad74304a2" />
<img width="1517" height="892" alt="Screenshot 2025-12-27 175227" src="https://github.com/user-attachments/assets/13f666e2-3097-4c25-97a8-584e2239f464" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
