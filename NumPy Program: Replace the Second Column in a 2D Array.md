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

```
import numpy as np

a = np.array([[1, 2, 3],
                [4, 5, 6],
                [7, 8, 9]])

new_col = np.array([10, 11, 12])

a = np.delete(a, 1, axis=1)
a = np.insert(a, 1, new_col, axis=1)

print("Updated array:\n", a)
```

## Output
<img width="1920" height="1080" alt="Screenshot (132)" src="https://github.com/user-attachments/assets/6c6c11cb-4f26-4c2c-91dd-089fcbb25035" />

## Result
Thus, the program is executed successfully.
