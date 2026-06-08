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
import numpy as np


x = np.array([10, 25, 30, 5, 18])
y = np.array([8, 25, 20, 10, 15])


condition = x >= y 

indices = np.where(condition)[0]


print("Array x:", x)
print("Array y:", y)
print("Indices where x >= y:", indices)
```

## Output
<img width="414" height="110" alt="image" src="https://github.com/user-attachments/assets/79952070-bee5-4642-ac9b-ab801d547c26" />

## Result
a Python program using NumPy that finds the indices where elements in array x are greater than or equal to their corresponding elements in array y is executed successfully.
