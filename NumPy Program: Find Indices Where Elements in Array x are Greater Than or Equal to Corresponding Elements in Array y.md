# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## Program

```
Developed By : Kalpanaa Babu T M
Reg No : 212224230112

import numpy as np  
x=eval(input()) 
y=eval(input()) 
l1=np.array(x) 
l2=np.array(y) 
print(np.where(l1>l2)) 
print(np.where(l1==l2))
```

## Output

<img width="808" height="229" alt="image" src="https://github.com/user-attachments/assets/a3d70746-0db6-45ea-89ee-e173a2b79ac9" />

## Result

Thus the output is executed successfully.
