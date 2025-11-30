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
    'name': ['Anil', 'Bina', 'Chitra', 'Deepak', 'Esha'],
    'score': [85, 92, 78, 90, 88],
    'attempts': [1, 3, 2, 1, 2],
    'qualify': ['yes', 'yes', 'no', 'yes', 'yes']
}

labels = ['a', 'b', 'c', 'd', 'e']

df = pd.DataFrame(exam_data, index=labels)
print(df)

```

## Output
<img width="526" height="421" alt="image" src="https://github.com/user-attachments/assets/b9d932d6-973c-4e51-a3e1-1dea337278b3" />

## Result
Thus, the program is executed successfully and the DataFrame is displayed with custom index labels.
