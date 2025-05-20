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
~~~
import pandas as pd
import numpy as np

exam_data = {
    'name': ['Anu', 'Bala', 'Chitra', 'David', 'Eva'],
    'score': [85, 92, 76, 88, 90],
    'attempts': [1, 2, 1, 3, 2],
    'qualify': ['yes', 'yes', 'no', 'yes', 'yes']
}

labels = ['a', 'b', 'c', 'd', 'e']

df = pd.DataFrame(exam_data, index=labels)

# Display output
print("Result:\n", df)
~~~

## Output
![Screenshot 2025-05-20 203856](https://github.com/user-attachments/assets/8808b1f8-cb55-4bf1-b805-89bb337d3514)

## Result
Thus the program has been successfully executed
