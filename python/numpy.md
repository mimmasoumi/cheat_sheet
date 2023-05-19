# cheat sheet for NumPy

- **Import NumPy:**
`import numpy as np`

### Creating Arrays:

- create an array from a list
`arr1 = np.array([1, 2, 3])`

- create an array of zeros
`arr2 = np.zeros((3, 4))`

- create an array of ones
`arr3 = np.ones((2, 2))`

- create an array of random values
`arr4 = np.random.rand(3, 4)`

- create an array with a range of values
`arr5 = np.arange(10)`

- create an array with evenly spaced values
`arr6 = np.linspace(0, 1, num=5)`

### Array Attributes:

- get the shape of an array
`arr.shape`

- get the number of dimensions of an array
`arr.ndim`

- get the data type of an array
`arr.dtype`

- get the size (total number of elements) of an array
`arr.size`

- get the itemsize (memory usage per element) of an array
`arr.itemsize`

- get the total number of bytes used by an array
`arr.nbytes`

### Indexing and Slicing:

- indexing
`arr[0]` first element
`arr[-1]`  last element
`arr[2,3]`  element at row 2, column 3

- slicing
`arr[0:3]`  first three elements
`arr[:, 0]`  first column
`arr[1:3, 2:4]`  elements in rows 1-2 and columns 2-3

### Mathematical Operations:

- scalar addition
`arr + 2`

- scalar multiplication
`arr * 2`

- element-wise addition
`arr1 + arr2`

- element-wise multiplication
`arr1 * arr2`

- dot product of two arrays
`np.dot(arr1, arr2)`

- sum of all elements in an array
`np.sum(arr)`

- mean of all elements in an array
`np.mean(arr)`

- standard deviation of all elements in an array
`np.std(arr)`

- maximum and minimum values in an array
`np.max(arr)`
`np.min(arr)`

### Array Manipulation:

- reshape an array
`arr.reshape((3, 4))`

- flatten an array
`arr.flatten()`

- concatenate two arrays (along rows)
`np.concatenate((arr1, arr2), axis=0)`

- stack two arrays vertically
`np.vstack((arr1, arr2))`

- stack two arrays horizontally
`np.hstack((arr1, arr2))`
