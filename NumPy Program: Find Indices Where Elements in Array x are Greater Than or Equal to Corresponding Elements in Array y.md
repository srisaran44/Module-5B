# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program

Add code here
import numpy as np

# Program to find indices where x >= y
def find_indices(x, y):
    # Condition check
    condition = x >= y
    # np.where returns indices where condition is True
    indices = np.where(condition)[0]
    return indices

# Driver code
x = np.array([5, 8, 12, 3, 7])
y = np.array([4, 10, 12, 2, 9])

print("Array x:", x)
print("Array y:", y)

result = find_indices(x, y)
print("Indices where x >= y:", result)

## Output
<img width="1040" height="732" alt="image" src="https://github.com/user-attachments/assets/b0b2de6e-aaa3-4c09-ae1b-d775f86e5244" />

## Result
