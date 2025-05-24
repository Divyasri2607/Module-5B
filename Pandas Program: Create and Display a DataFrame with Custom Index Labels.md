# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```
import pandas as pd
import numpy as np

exam_data = {
    'name': ['Ankit', 'Divya', 'Priya', 'Bhoopesh', 'Neha'],
    'score': [88.5, 92.0, 79.5, 85.0, 90.5],
    'attempts': [1, 3, 2, 2, 1],
    'qualify': ['yes', 'no', 'yes', 'yes', 'no']
}

labels = ['a', 'b', 'c', 'd', 'e']

df = pd.DataFrame(exam_data, index=labels)

print("Custom DataFrame with Index Labels:")
print(df)
```
## Output
![image](https://github.com/user-attachments/assets/0376bd24-b04b-48ba-b9e8-ea24e2208d25)

## Result
Program has been executed successfully.
