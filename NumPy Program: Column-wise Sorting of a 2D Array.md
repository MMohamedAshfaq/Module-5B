# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
Add code here
~~~
import numpy as np

arr = np.array([[12, 5, 7],
                [4, 8, 6],
                [9, 3, 1]])

# Column-wise sort (axis=0)
sorted_arr = np.sort(arr, axis=0)

# Display output
print("Original Array:\n", arr)
print("Column-wise Sorted Array:\n", sorted_arr)

~~~
## Output
![Screenshot 2025-05-20 115207](https://github.com/user-attachments/assets/ff410d08-7269-49c8-9070-a5bef63c997c)

## Result
Thus the program has been successfully executed
