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
'''
program to find 1-norm of a mmatrix.
Developed by:CHANDRU.P
Register Number:23007250
'''
import numpy as np
array=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix

'''
program to find 2-norm of a mmatrix.
Developed by:CHANDRU.P
Register Number:23007250
'''
import numpy as np
array1=([[1,2],[3,4]])
array2=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix


'''
program to find infinity-norm of a mmatrix.
Developed by:CHANDRU.P
Register Number:23007250
'''
import numpy as np
array=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-28 084612](https://github.com/chandru174642/Norm-of-a-matrix/assets/139841798/4c9f276f-ab0f-49c0-875a-b7c2f985eb99)

<br>
<br>

### 2-Norm of a Matrix
![Screenshot 2023-12-28 085034](https://github.com/chandru174642/Norm-of-a-matrix/assets/139841798/0971cf2d-ed8a-467e-adb4-de6e4ce1a056)

<br>
<br>

### Infinity Norm of a Matrix
![Screenshot 2023-12-28 085057](https://github.com/chandru174642/Norm-of-a-matrix/assets/139841798/46b3f85a-e9f7-4e52-8f3c-e4c374addc87)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
