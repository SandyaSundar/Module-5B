# NumPy Program: Replace elements in Array

## 🎯 Aim
To write a **NumPy** program to replace all the elements in the array which are greater than 25 with  1 otherwise.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Display Result**: Print the updated array with the replaced elements.

## 🧾 Program

```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a = eval(input())
a = np.array(a)
result = (a>25) * 1
print(result)
```

## Output

<img width="843" height="866" alt="image" src="https://github.com/user-attachments/assets/c7fa64c0-6198-4e5a-af3f-1076a70fc236" />

## Result
Thus the given python program has been executed successfully.
