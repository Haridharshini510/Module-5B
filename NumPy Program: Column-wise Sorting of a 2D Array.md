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
array = np.array([[9, 2, 7],
                  [4, 6, 1],
                  [8, 5, 3]])
sorted_array = np.sort(array, axis=0)
print("Original Array:")
print(array)
print("Column-wise Sorted Array:")
print(sorted_array)

```
## Output
<img width="576" height="508" alt="image" src="https://github.com/user-attachments/assets/b1a5c6fa-5f9b-4b7d-9bda-7f6dabbbbddf" />

## Result
Thus, the program was executed successfully and the predefined 2D array was sorted column-wise using NumPy.
