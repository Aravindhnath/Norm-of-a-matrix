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

# Register No:22009024
# Developed By:Aravindhnath T R
## Program:
```Python

# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix
import numpy as np 
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![Screenshot_20230123_062640](https://user-images.githubusercontent.com/118790841/214047504-0d83f0a5-86c4-485b-902c-46696dac5e1f.png)

### 2-Norm of a Matrix
![Screenshot_20230123_062737](https://user-images.githubusercontent.com/118790841/214047577-493ea7b8-85de-4e22-a665-1ec04c0ab5d4.png)

### Infinity Norm of a Matrix
![Screenshot_20230123_062820](https://user-images.githubusercontent.com/118790841/214047604-6927a764-0c82-432a-99c8-128917690662.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
