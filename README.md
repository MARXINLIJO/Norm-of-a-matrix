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
# Register No:23013468
# Developed By:MARXIN LIJO M
# 1-Norm of a Matrix
```
import numpy as np
array=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
# 2-Norm of a Matrix
```
import numpy as np
array1=([[1,2],[3,4]])
array2=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
# Infinity Norm of a Matrix
```
import numpy as np
array1=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/MARXINLIJO/Norm-of-a-matrix/assets/145742540/2eaf4155-739f-42d0-a6e2-9c3d540c57c8)


### 2-Norm of a Matrix

![image](https://github.com/MARXINLIJO/Norm-of-a-matrix/assets/145742540/93d72217-75f2-4e40-81ea-9d7f1bd3a0d8)

### Infinity Norm of a Matrix
![image](https://github.com/MARXINLIJO/Norm-of-a-matrix/assets/145742540/e9b02e5a-d201-4bf3-88e5-0e320fed132f)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
