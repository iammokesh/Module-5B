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
```python
import pandas as pd

# Create first DataFrame
student_data1 = {
    'student_id': [1, 2, 3, 4, 5],
    'name': ['Alex', 'Amy', 'Allen', 'Alice', 'Ayoung'],
    'marks': [50, 60, 70, 80, 90]
}

df1 = pd.DataFrame(student_data1)

# Create second DataFrame
student_data2 = {
    'student_id': [6, 7, 8, 9, 10],
    'name': ['Billy', 'Brian', 'Bran', 'Bryce', 'Betty'],
    'marks': [55, 65, 75, 85, 95]
}

df2 = pd.DataFrame(student_data2)

# Concatenate DataFrames row-wise
new_df = pd.concat([df1, df2], axis=0)

# Display the combined DataFrame
print(new_df)

```
## Output
<img width="631" height="237" alt="Screenshot 2026-05-31 183311" src="https://github.com/user-attachments/assets/20fd103f-0637-4efb-8c46-18d5370c5496" />

## Result
By using python the code was executed successfully.
