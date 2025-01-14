<p>
  <img align="center" src="https://protoinfrastack-myfirstbucketb8884501-fnnzvxt2ee5v.s3.amazonaws.com/lAeXN1za8y45Vidyt7JGGcJgewRAXsrDjyRu.gif" alt="GIF Animation" ,hight="300",width="500"/>
</p>
#Element-wise arithmetic operations:
#Addition, subtraction, multiplication, and division of arrays with scalars or other arrays.

#Array addition
# Array addition
array1 = np.array([1, 2, 3])
array2 = np.array([4, 5, 6])
result = array1 + array2
print(result)  # [5 7 9]
Create Array of Fixed Size
Often, the element is of an array is originally unknown, but its size is known. Hence, NumPy offers several functions to create arrays with initial placeholder content.

This minimize the necessity of growing arrays, an expensive operation. For example: np.zeros, np.ones, np.full, np.empty, etc.

 Reshaping Array using Reshape Method
Reshaping array: We can use reshape method to reshape an array.

Consider an array with shape (a1, a2, a3, …, aN). We can reshape and convert it into another array with shape (b1, b2, b3, …, bM). The only required condition is a1 x a2 x a3 … x aN = b1 x b2 x b3 … x bM. (i.e. the original size of the array remains unchanged.)

# Reshaping 3X4 array to 2X2X3 array
arr = np.array([[1, 2, 3, 4],
                [5, 2, 4, 2],
                [1, 2, 0, 1]])

newarr = arr.reshape(2, 2, 3)

print ("Original array:\n", arr)
print("---------------")
print ("Reshaped array:\n", newarr)