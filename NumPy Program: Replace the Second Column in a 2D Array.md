# NumPy Program: Replace the Second Column in a 2D Array

## Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## Program

```
Developed By : Kalpanaa Babu T M
Reg No : 212224230112

import numpy as np

rows = int(input("Enter number of rows: "))
cols = int(input("Enter number of columns: "))

data = []
for i in range(rows):
    row = list(map(int, input(f"Enter row {i+1} elements: ").split()))
    data.append(row)

arr = np.array(data)

new_col = list(map(int, input("Enter new column elements: ").split()))
new_col = np.array(new_col)

arr_del = np.delete(arr, 1, axis=1)
arr_ins = np.insert(arr_del, 1, new_col, axis=1)

print("Original Array:\n", arr)
print("Updated Array:\n", arr_ins)
```

## Output

<img width="959" height="502" alt="image" src="https://github.com/user-attachments/assets/8ea99efb-656a-4d57-90bb-8f2aba38b70f" />

## Result

Thus the output is executed successfully.
