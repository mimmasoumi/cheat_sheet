# cheat sheet for NumPy:

1. Import NumPy: `import numpy as np`

2. Create an array: `arr = np.array([1, 2, 3])`

3. Create a 2D array: `arr_2d = np.array([[1, 2, 3], [4, 5, 6]])`

4. Get the shape of an array: `arr.shape`

5. Get the size of an array: `arr.size`

6. Get the data type of an array: `arr.dtype`

7. Reshape an array: `arr.reshape((2, 2))`

8. Concatenate arrays vertically: `np.vstack((arr1, arr2))`

9. Concatenate arrays horizontally: `np.hstack((arr1, arr2))`

10. Generate an array of zeros: `np.zeros((2, 2))`

11. Generate an array of ones: `np.ones((2, 2))`

12. Generate a range of values: `np.arange(0, 10, 2)`

13. Generate evenly spaced values: `np.linspace(0, 1, 5)`

14. Add two arrays: `arr1 + arr2`

15. Subtract two arrays: `arr1 - arr2`

16. Multiply two arrays: `arr1 * arr2`

17. Divide two arrays: `arr1 / arr2`

18. Dot product of two arrays: `np.dot(arr1, arr2)`

19. Transpose an array: `arr.T`

20. Find the minimum value in an array: `np.min(arr)`

21. Find the maximum value in an array: `np.max(arr)`

22. Find the sum of values in an array: `np.sum(arr)`

23. Find the mean value in an array: `np.mean(arr)`

24. Find the standard deviation of values in an array: `np.std(arr)`

25. Find the index of the minimum value in an array: `np.argmin(arr)`

26. Find the index of the maximum value in an array: `np.argmax(arr)`

27. Sort an array in ascending order: `np.sort(arr)`

28. Sort an array in descending order: `np.sort(arr)[::-1]`

29. Get unique values in an array: `np.unique(arr)`

30. Save an array to a file: `np.save('filename.npy', arr)`

31. Load an array from a file: `np.load('filename.npy')`
