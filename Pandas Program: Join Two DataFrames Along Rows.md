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

# DataFrames
data1 = {
    's_id': ['S1', 'S2', 'S3', 'S4', 'S5'],
    'name': ['Dan', 'Ryder', 'Bryce', 'Bernal', 'Kwame'],
    'marks': [200, 210, 190, 222, 199]
}

data2 = {
    's_id': ['S4', 'S5', 'S6', 'S7', 'S8'],
    'name': ['Scart', 'Willy', 'Dani', 'Kaise', 'Madeeha'],
    'marks': [201, 200, 198, 219, 201]
}

# Create DataFrames
df1 = pd.DataFrame(data1)
df2 = pd.DataFrame(data2)

# Display original DataFrames
print("Original DataFrames:")
print(df1)
print("-------------------------------------")
print(df2)

# Concatenate along rows
print("\nJoin the said two DataFrames along rows:")
result = pd.concat([df1, df2], axis=0)
print(result)

```
## Output
<img width="708" height="484" alt="image" src="https://github.com/user-attachments/assets/cc25970e-eca5-4c34-8b3d-58123593996d" />

## Result
Thus, the program is executed successfully and the two DataFrames are concatenated along rows.
