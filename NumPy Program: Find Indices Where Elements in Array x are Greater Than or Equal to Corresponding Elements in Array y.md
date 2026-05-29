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

```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

x = eval(input())
y = eval(input())

x = np.array(x)
y = np.array(y)

greater_positions = np.where(x>y)
equal_positions = np.where(x == y)

print(greater_positions)
print(equal_positions)
```

## Output
<img width="917" height="908" alt="image" src="https://github.com/user-attachments/assets/aa5ea53e-554a-44ea-ad46-b190df0f7265" />

## Result
Thus the given python program has been executed successfully.
