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
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(f"{norm1:.2f}")





# 2-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")





# Infinity Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm3=np.linalg.norm(A,np.inf)
print(f"{norm3:.2f}")





```
## Output:
### 1-Norm of a Matrix
<br><img width="1380" height="850" alt="Screenshot 2025-12-18 102504" src="https://github.com/user-attachments/assets/37539f0e-f1fd-47b6-b87f-5a031cb021e8" />

<br>
<br>

### 2-Norm of a Matrix
<br>
<br><img width="1219" height="831" alt="Screenshot 2025-12-18 102524" src="https://github.com/user-attachments/assets/f618bec8-1560-41ae-9a9c-49aaae04f761" />

<br>

### Infinity Norm of a Matrix
<br>
<br><img width="826" height="803" alt="Screenshot 2025-12-18 102542" src="https://github.com/user-attachments/assets/e7c61068-df86-44df-89dc-7592a578482c" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
