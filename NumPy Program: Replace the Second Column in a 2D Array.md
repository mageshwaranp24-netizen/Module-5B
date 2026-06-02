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

rows = int(input("Enter number of rows: "))
cols = int(input("Enter number of columns: "))

print("Enter array elements:")
arr = np.array([[int(input()) for j in range(cols)] for i in range(rows)])

print("Enter elements of the new column:")
new_col = np.array([int(input()) for i in range(rows)])

arr = np.delete(arr, 1, axis=1)

arr = np.insert(arr, 1, new_col, axis=1)

print("Updated Array:")
print(arr)
```

## Output
<img width="753" height="488" alt="image" src="https://github.com/user-attachments/assets/525f87d9-6e5a-47dd-8a64-63a85b1e51e5" />

## Result
Thus the NumPy program that deletes the second column from a given 2D array and inserts a new column at the same position was ecexuted successfully.
