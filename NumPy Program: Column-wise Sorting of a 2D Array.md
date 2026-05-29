# NumPy Program: Row-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each row of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=1` to sort each row in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the row-wise sorted array.

## 🧾 Program
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a = eval(input())
a = np.array(a)
print("Given array")
print(f" {a}")
a = np.sort(a, axis=1)
```

## Output
<img width="691" height="915" alt="image" src="https://github.com/user-attachments/assets/5f520a2d-b89e-4394-abfa-deb47619e23e" />

## Result
Thus the given python program has been executed successfully.
