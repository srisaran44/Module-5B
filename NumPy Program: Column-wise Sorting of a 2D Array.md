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
import numpy as np

# Program to sort each column of a 2D array
def sort_columns(arr):
    # np.sort with axis=0 → sorts column-wise
    sorted_arr = np.sort(arr, axis=0)
    return sorted_arr

# Driver code
array_2d = np.array([[12, 7, 9],
                     [5, 15, 3],
                     [8, 2, 10]])

print("Original Array:\n", array_2d)
print("\nColumn-wise Sorted Array:\n", sort_columns(array_2d))


## Output
<img width="958" height="750" alt="image" src="https://github.com/user-attachments/assets/993df350-f32a-4fcb-ad00-191cd7789f53" />


## Result
