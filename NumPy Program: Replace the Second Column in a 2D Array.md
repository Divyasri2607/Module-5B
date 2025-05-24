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

original_array = eval(input())
original_array = np.array(original_array)
new_column = eval(input())
new_column = np.array(new_column)

modified_array = np.delete(original_array, 1, axis=1)
updated_array = np.insert(modified_array, 1, new_column, axis=1)

print("\nOriginal Array:")
print(original_array)

print("\nUpdated Array (after replacing second column):")
print(updated_array)

```
## Output
![image](https://github.com/user-attachments/assets/101c5d5a-b351-4ac0-b570-f9c812dedc78)

## Result
Program has been executed successfully.
