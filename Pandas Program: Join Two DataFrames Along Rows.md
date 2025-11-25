# Pandas Program: Join Two DataFrames Along Rows

## AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## Program

```
Developed By : Kalpanaa Babu T M
Reg No : 212224230112

import pandas as pd
a=eval(input())
b=eval(input())
df1=pd.DataFrame(a)
df2=pd.DataFrame(b)
print("Original DataFrames:")
print(df1)
print("-------------------------------------")
print(df2)
print()
mer=pd.concat([df1,df2])
print("Join the said two dataframes along rows:")
print(mer)
```

## Output

<img width="1245" height="815" alt="image" src="https://github.com/user-attachments/assets/cee03689-55d6-4cf2-a0cd-e0189886e038" />

## Result

Thus the output is executed successfully.
