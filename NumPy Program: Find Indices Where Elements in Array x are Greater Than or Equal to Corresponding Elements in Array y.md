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

x = np.array([5, 2, 8, 6, 3])
y = np.array([3, 2, 7, 9, 3])
print(x>y)
print(x==y)
indices = np.where(x >= y)
print(indices)

```

## Output

![image](https://github.com/user-attachments/assets/0743800b-3d82-4475-808b-ae0fb5b7127f)

## Result

Thus implemented the python program to find the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.
