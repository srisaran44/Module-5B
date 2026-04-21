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
import pandas as pd

# Program to join two DataFrames row-wise
def join_dataframes():
    # First DataFrame
    df1 = pd.DataFrame({
        'ID': [1, 2, 3],
        'Name': ['Alice', 'Bob', 'Charlie']
    })

    # Second DataFrame
    df2 = pd.DataFrame({
        'ID': [4, 5],
        'Name': ['David', 'Eva']
    })

    # Row-wise concatenation
    new_df = pd.concat([df1, df2], axis=0)

    print("DataFrame 1:\n", df1, "\n")
    print("DataFrame 2:\n", df2, "\n")
    print("Joined DataFrame (Row-wise):\n", new_df)

# Driver code
join_dataframes()

Add code here

## Output
<img width="1157" height="744" alt="image" src="https://github.com/user-attachments/assets/a0a12ed3-8634-4ecc-b9d5-0ca2637fce93" />


## Result
