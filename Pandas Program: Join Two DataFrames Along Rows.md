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
    'name': ['Ankit', 'Divya', 'Priya'],
    'score': [85, 92, 78],
    'attempts': [1, 2, 1]
}
df1 = pd.DataFrame(student_data1)

student_data2 = {
    'name': ['John', 'Neha', 'Ravi'],
    'score': [88, 90, 76],
    'attempts': [2, 1, 3]
}
df2 = pd.DataFrame(student_data2)

combined_df = pd.concat([df1, df2], axis=0, ignore_index=True)

print("Combined DataFrame (Row-wise):")
print(combined_df)

```
## Output
![image](https://github.com/user-attachments/assets/28a2d6b3-d05f-46d7-9660-3f5de845732b)

## Result
Program has been executed successfully.
