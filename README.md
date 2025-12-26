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
```
import numpy as np

array = np.array([[7, 67, 87],
                [43, 54, 98],
                [78, 8, 9]])

sorted_array = np.sort(array, axis=0)

print("Original array:\n", array)
print("Column-wise sorted array:\n", sorted_array)
```
## Output
<img width="1920" height="1080" alt="Screenshot (130)" src="https://github.com/user-attachments/assets/70b0433e-1dbb-42e0-b1d8-ed1c0d3bf9b2" />

## Result
Thus, the program is executed successfully.
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

```
import numpy as np

x = np.array([1, 30, 54, 70, 22])
y = np.array([2, 7, 80, 11, 45])

indices = np.where(x >= y)
print("Indices where x >= y:", indices[0])
```

## Output
<img width="1920" height="1080" alt="Screenshot (131)" src="https://github.com/user-attachments/assets/3ba2dc6b-d0a0-46f9-a812-751910584ab7" />

## Result
Thus, the program is executed successfully.
