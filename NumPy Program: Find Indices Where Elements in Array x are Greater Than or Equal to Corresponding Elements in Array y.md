# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
```python
import numpy as np

# Input arrays
x = np.array(list(map(int, input().split())))
y = np.array(list(map(int, input().split())))

# Find indices where x >= y
indices = np.where(x >= y)

# Print indices
print("Indices where x >= y:")
print(indices[0])
```
## Output
<img width="393" height="95" alt="Screenshot 2026-05-31 151133" src="https://github.com/user-attachments/assets/1d2982f9-b854-41f1-9f73-5de368525744" />


## Result
By using python the code was executed successfully.
