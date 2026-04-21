# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
Add code here
import pandas as pd

# Program to create DataFrame with custom index labels
def create_dataframe():
    # Dictionary data
    data = {
        'Name': ['Alice', 'Bob', 'Charlie', 'David'],
        'Age': [24, 27, 22, 32],
        'City': ['New York', 'Los Angeles', 'Chicago', 'Houston']
    }
    
    # Custom index labels
    index_labels = ['Row1', 'Row2', 'Row3', 'Row4']
    
    # Create DataFrame
    df = pd.DataFrame(data, index=index_labels)
    
    print("DataFrame with Custom Index Labels:\n")
    print(df)

# Driver code
create_dataframe()


## Output
<img width="1063" height="783" alt="image" src="https://github.com/user-attachments/assets/c3700dc2-787e-43f6-b07b-887a9a429c56" />

## Result
