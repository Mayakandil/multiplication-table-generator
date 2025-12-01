# Multiplication Table Generator 📘

This is a simple Python project that generates a multiplication table using nested list comprehensions.  
The size of the table is controlled by the variable `n`, and the program dynamically creates a list of lists representing the table.

---

## 🔢 Example Code

```python
n = 3
table = [[i * j for j in range(1, i + 1)] for i in range(1, n + 1)]
print(table)

#📌 How It Works
- n determines how many rows the multiplication table will contain.
- A nested list comprehension is used to build the table:
    - Outer loop → controls the row (i)
    -Inner loop → generates values for each row (j)
- Each row contains values from 1 × i up to i × i.


#🧪 Example Output
For n = 3, the output will be:
[[1], [2, 4], [3, 6, 9]]


# 🚀 How to Run
- Make sure you have Python installed.
- Save the script in a file, for example:
multiplication.py
- In a terminal, run:
python multiplication.py

# 📚 Features
- Uses list comprehensions for clean and - efficient code.
- Automatically builds a dynamic - multiplication structure.
- Easy to modify by changing the value of n.

# 🔮 Possible Improvements
- Print the table in a formatted grid.
- Allow user input for n.
- Save the output to a file.
- Generate a full multiplication table (n × n instead of triangular).


