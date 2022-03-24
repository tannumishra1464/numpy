#Welcome to numpy module.
import numpy as np
myarr = np.array([[6,4,34,67]],np.int64)
myarr
array([[ 6,  4, 34, 67]])
myarr[0,1]
4
myarr.dtype
dtype('int64')
myarr.shape
(1, 4)
myarr.size
4
myarr[0,1] = 45
myarr
array([[ 6, 45, 34, 67]])

#Array creation : Conversion from other python structures.
list1 = np.array([[1,2,3],[4,5,6],[5,0,5]])
list1
array([[1, 2, 3],
       [4, 5, 6],
       [5, 0, 5]])
list1.max()
6
list1.min()
0
list1.dtype
dtype('int64')
list1.size
9
list1.shape
(3, 3)
np.array({25,34,56})
array({56, 25, 34}, dtype=object)
