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
```python
Developed by: DEVADARSHAN A S
RegisterNumber: 212222110007

(i) 1-norm
# program to find 1-norm of a matrix.
import numpy as np 
a=np.array(eval(input()))
n = np.linalg.norm(a,1)
print("{:.2f}".format(n))



(ii) 2-norm
# program to find 2-norm of a matrix.
import numpy as np 
a=np.array(eval(input()))
n = np.linalg.norm(a,2)
print("{:.2f}".format(n))


(iii) 3-infinity
# program to find infinity-norm of a matrix.
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/DEVADARSHAN2/Norm-of-a-matrix/assets/119432150/6a562120-bde7-43de-85d6-52728c26c78e)
### 2-Norm of a Matrix


![image](https://github.com/DEVADARSHAN2/Norm-of-a-matrix/assets/119432150/a07d1a63-c679-4473-93ce-6186058a52a0)
### Infinity Norm of a Matrix
![image](https://github.com/DEVADARSHAN2/Norm-of-a-matrix/assets/119432150/8351ab6e-19d6-4b80-9e1d-c786d2b1e219)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
