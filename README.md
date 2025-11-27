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
# Register No:25016457
# Developed By:s.deepakkumar
# 1-Norm of a Matrix```
```
import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,1)
print(f"{norm1:.2f}")
```




# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: deepakkumar s
RegisterNumber:25016457
'''
import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,2)
print(f"{norm1:.2f}")
```




# Infinity Norm of a Matrix
```
'''
Program to find 3-norm of a matrix.
RegisterNumber:25016457
nAME:DEEPAKKUMAR S
'''
import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,np.inf)
print(f"{norm1:.2f}")
```






## Output:
### 1-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot 2025-11-27 104941" src="https://github.com/user-attachments/assets/506f797e-2544-4374-9ff5-5a2804f7baab" />

<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot 2025-11-27 105117" src="https://github.com/user-attachments/assets/f93f406c-7382-46fe-ad4c-05b5d0fbd554" />

<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="1920" height="1080" alt="Screenshot 2025-11-27 105142" src="https://github.com/user-attachments/assets/49098e9f-9fcd-4eb0-a7d7-f85f0f9ebc8a" />
<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
