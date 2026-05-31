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
```python
import numpy as np

# Input rows and columns
r = int(input("Enter number of rows: "))
c = int(input("Enter number of columns: "))

# Input array elements
print("Enter array elements:")
arr = []
for i in range(r):
    row = list(map(int, input().split()))
    arr.append(row)

arr = np.array(arr)

# Input new column elements
print("Enter new column elements:")
new_col = list(map(int, input().split()))

# Delete second column (index 1)
arr = np.delete(arr, 1, axis=1)

# Insert new column at second position
arr = np.insert(arr, 1, new_col, axis=1)

# Display result
print("Updated Array:")
print(arr)
```
## Output
<img width="447" height="62" alt="Screenshot 2026-05-29 190231" src="https://github.com/user-attachments/assets/6687939f-ea27-44d4-ad9c-ba35d332c0a3" />



## Result
By using python the code was executed successfully.
