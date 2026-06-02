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
rows = int(input("Enter number of rows: "))
cols = int(input("Enter number of columns: "))
print("Enter the array elements:")
arr = np.array([[int(input()) for j in range(cols)] for i in range(rows)])

sorted_arr = np.sort(arr, axis=0)

print("Original Array:")
print(arr)

print("Column-wise Sorted Array:")
print(sorted_arr)
```

## Output
<img width="496" height="381" alt="image" src="https://github.com/user-attachments/assets/22c23d0a-94e2-434b-900b-e21e2e276c31" />

## Result
Thus the  NumPy program that sorts the elements in each column of a given 2D array in ascending order was executed successfully.
