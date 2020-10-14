# learning-numpy
# generating data
import numpy as np 
arr=np.array([1,2,3]) it can gernerate a 1D array.
arr=np.arrange(0,10,2) it can gernerate a array with a fixed-step.
arr.reshape(m,n) itcan transform a matrix into the size m*n.
arr=np.zeros((3,3)) it can initialize a matrix with 0.
arr=np.ones((3,3)) it can initialize a matrix with 1.
arr=np.random.randint(0,10,(3,3)) it can gernerate a  3*3 matrix randomly between 0 and 10.
arr=np.linspace(0,100,100) it can generate a specified size array with fixed-step.
# matrix operation
for vectors' inner product:np.dot()
for the element-wise product of matrixs:np.multiply(A,B) or A*B
for matrixs multiply:np.matmul(A,B) or A@B
# sliceing
arr[:1,:] is the first line of arr.
arr[:,:1] is the first column of arr.
the two sides of : is the position of sliceing.  
e.g.arr[2:3,:] is the third line of arr. and their default value are 0 and len(arr) respectively. 
