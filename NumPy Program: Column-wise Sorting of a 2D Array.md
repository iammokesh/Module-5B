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
```python
import numpy as np

# Input rows and columns
r = int(input())
c = int(input())

# Input array elements
arr = []
for i in range(r):
    row = list(map(int, input().split()))
    arr.append(row)

a = np.array(arr)

# Sort each column in ascending order
sorted_array = np.sort(a, axis=0)

# Display output
print("Original Array:")
print(a)

print("Column-wise Sorted Array:")
print(sorted_array)
```
## Output
<img width="565" height="169" alt="Screenshot 2026-05-31 151537" src="https://github.com/user-attachments/assets/439dfe75-f285-4a8c-bd25-e9ee71413916" />



## Result
By using python the code was executed sucessfully
