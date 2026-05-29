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
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import pandas as pd

a = eval(input())
b = eval(input())
a = pd.DataFrame(a)
b = pd.DataFrame(b)
print("Original DataFrames:")
print(a)
print("-------------------------------------")
print(b)
merge = pd.concat([a, b])
print()
print("Join the said two dataframes along rows:")
print(merge)
```

## Output

<img width="1162" height="910" alt="image" src="https://github.com/user-attachments/assets/fca6fca8-bc8a-424d-8099-54c4bcbbf51a" />

## Result
Thus the given python program has been executed successfully.
