# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
import pandas as pd

student_data1 = {
    'Name': ['John', 'Alice', 'Bob'],
    'Marks': [85, 90, 78]
}

df1 = pd.DataFrame(student_data1)
student_data2 = {
    'Name': ['David', 'Emma', 'Sophia'],
    'Marks': [88, 92, 81]
}

df2 = pd.DataFrame(student_data2)
combined_df = pd.concat([df1, df2], axis=0)
print(combined_df)
```

## Output
<img width="750" height="432" alt="image" src="https://github.com/user-attachments/assets/258e864b-1d9c-4930-baa7-190a8fbe547c" />

## Result
Thus the Python program using Pandas to join two DataFrames along rows (row-wise concatenation) and assign all data to a new DataFrame is executed successfully.
