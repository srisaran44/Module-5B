# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program

Add code here
import numpy as np

# Program to delete and insert column in 2D array
def replace_second_column(arr, new_col):
    # Delete the second column (index = 1)
    arr_deleted = np.delete(arr, 1, axis=1)
    
    # Insert new column at index 1
    arr_new = np.insert(arr_deleted, 1, new_col, axis=1)
    return arr_new

# Driver code
array_2d = np.array([[10, 20, 30],
                     [40, 50, 60],
                     [70, 80, 90]])

print("Original Array:\n", array_2d)

new_column = np.array([100, 200, 300])  # New column to insert
result = replace_second_column(array_2d, new_column)

print("\nArray after replacing second column:\n", result)


## Output
<img width="852" height="710" alt="image" src="https://github.com/user-attachments/assets/5163f0b6-fdc6-4f85-953a-30612f34e234" />

## Result
