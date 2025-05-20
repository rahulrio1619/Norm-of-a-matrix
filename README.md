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
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
norm = np.linalg.norm(a,1)
print(norm)
# 2-Norm of a Matrix
import numpy as np
a = np.array(eval(input()))
norm = np.linalg.norm(a,2)
print(f"{norm:.2f}")
# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
norm = np.linalg.norm(a,np.inf)
print(f"{norm:.2f}")
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/c32fae0f-bfeb-4287-abe4-c0cfabc08abd)

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/348bbf6d-4307-498f-aad3-8632c5071765)

### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/4dd9f294-e823-4f93-a57f-7afdd087eb16)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
