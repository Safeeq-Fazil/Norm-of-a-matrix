# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()    
2. 2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
# 1-Norm of a Matrix
```
Python
# Register No: Safeeq Fazil.A
# Developed By: 212222240086


import numpy as np

mat= np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```



# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Safeeq Fazil.A
RegisterNumber: 212222240086
'''
import numpy as np

mat= np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

```



# Infinity Norm of a Matrix
```
#program to find the Infinity of a matrix and display the result in two decimal places.
#Developed by: Safeeq Fazil.A
#Register No: 212222240086


import numpy as np

mat=np.array(eval(input()))
ans= np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```




```
## Output:
## 1-Norm of a Matrix
![exp 7 1](https://github.com/Safeeq-Fazil/Norm-of-a-matrix/assets/118680361/14f59cea-b25a-4f8d-a779-f1e2017f2d01)


## 2-Norm of a Matrix
![exp 7 2](https://github.com/Safeeq-Fazil/Norm-of-a-matrix/assets/118680361/9547b155-6a37-4fbb-bcf7-9c26cc983015)


## Infinity Norm of a Matrix
![exp 7 3](https://github.com/Safeeq-Fazil/Norm-of-a-matrix/assets/118680361/5b6f9f29-d8da-4560-ac38-732b13d7bf9d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
