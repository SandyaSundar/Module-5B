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
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import pandas as pd
import numpy as np

data = eval(input())

df = pd.DataFrame(data)
df.index = list("ABCDEFGHIJ")

result = df[(df['perc'] >= 70) & (df['perc'] <= 90)]
print("Number of student whoes percentage more than 70:")
print(result)
```

## Output

<img width="1435" height="860" alt="image" src="https://github.com/user-attachments/assets/b569ea5e-4bb3-40a0-904b-c9898eb50757" />

## Result
Thus the given python program has been executed successfully.
