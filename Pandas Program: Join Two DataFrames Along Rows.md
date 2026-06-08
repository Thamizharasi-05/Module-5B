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

# First DataFrame
student_data1 = {
    'student_id': [1, 2, 3, 4, 5],
    'name': ['Alex', 'Amy', 'Allen', 'Alice', 'Ayoung'],
    'marks': [50, 60, 70, 80, 90]
}

# Second DataFrame
student_data2 = {
    'student_id': [6, 7, 8, 9, 10],
    'name': ['Billy', 'Brian', 'Bran', 'Bryce', 'Betty'],
    'marks': [55, 65, 75, 85, 95]
}

df1 = pd.DataFrame(student_data1)
df2 = pd.DataFrame(student_data2)

# Row-wise concatenation
new_df = pd.concat([df1, df2], axis=0)

print("Combined DataFrame:")
print(new_df)
```

## Output
<img width="1255" height="642" alt="image" src="https://github.com/user-attachments/assets/851ead2c-acb4-49fb-b8da-85cc0e71ca5e" />

## Result
Thus the given program executed Successfully.
