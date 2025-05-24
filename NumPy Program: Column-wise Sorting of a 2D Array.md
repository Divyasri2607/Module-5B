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

array_input = eval(input())
original_array = np.array(array_input)
sorted_array = np.sort(original_array, axis=0)

print("\nOriginal Array:")
print(original_array)

print("\nColumn-wise Sorted Array:")
print(sorted_array)

```
## Output
![image](https://github.com/user-attachments/assets/4aa833e4-00ed-40b0-ad59-173ed0a11879)

## Result
Program has been executed successfully.
