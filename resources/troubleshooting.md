# 🛠️ Troubleshooting & Debugging Guide

Stuck? Don't panic. Errors are the best way to learn programming. Use this guide to diagnose your issue before reaching out for help.

---

## 🧭 The "Debug Route" (Step-by-Step)
If you hit an error, follow these steps in order:

1. **Read the Last Line First:** The error message is almost always at the very bottom of the red block. That is where the actual problem is described.
2. **Copy & Paste the Error:** Copy the *last line* of the error into Google or ChatGPT. Add "Python" or "Pandas" to the search query.
3. **Check Your Indentation:** 90% of beginner errors are just missing spaces or extra tabs.
4. **Isolate the Variable:** Use `print()` statements above the error to see exactly what data is in your variables (e.g., `print(df.shape)` or `print(type(variable))`).
5. **Restart the Kernel:** In Colab, go to `Runtime > Restart Session` and run the cells again. Sometimes the "ghosts" of old variables cause the problem.

---

## 🚫 Common "Beginner" Errors

### 1. `NameError: name 'x' is not defined`
* **What it means:** You are trying to use a variable that doesn't exist yet.
* **The Route:** Did you run the cell where the variable was defined first? Did you make a typo?

### 2. `IndentationError: expected an indented block`
* **What it means:** You forgot to press Tab after a `:`, `if`, `for`, or `def` statement.
* **The Route:** Check the line *above* the error.

### 3. `ModuleNotFoundError: No module named 'x'`
* **What it means:** The library isn't installed.
* **The Route:** Add a new cell and type `!pip install library_name` at the top of your notebook.

### 4. `ValueError: operands could not be broadcast together...`
* **What it means:** You are trying to do math on two lists/arrays of different sizes.
* **The Route:** Check the `.shape` of your data. Are the rows and columns what you expected?

### 5. `IndexError: list index out of range`
* **What it means:** You asked for item #10 in a list that only has 5 items.
* **The Route:** Check the length of your list using `len(your_list)`.

### 6. `TypeError: can only concatenate str (not "int") to str`
* **What it means:** You are trying to combine text (string) and a number (int) using the `+` sign. 
* **The Route:** Convert the number to a string first: `print("Age: " + str(age))` or use an f-string: `print(f"Age: {age}")`.

### 7. `FileNotFoundError: [Errno 2] No such file or directory`
* **What it means:** Python cannot find the file you are trying to open.
* **The Route:** Check your current working directory by running `import os; print(os.getcwd())`. Ensure the file is in the right folder.

### 8. `KeyError: 'column_name'`
* **What it means:** You are trying to access a column in a Pandas DataFrame, but that exact name does not exist.
* **The Route:** Print the columns using `print(df.columns)`. Look for typos, extra spaces, or capitalization differences.

### 9. `AttributeError: 'NoneType' object has no attribute '...'`
* **What it means:** You are trying to use a function (like `.sort()` or `.drop()`) on a variable that is `None`.
* **The Route:** This often happens because methods like `df.drop()` modify the object *in place* and return `None`. Do not assign the result back to the variable if it's an "in-place" operation.

---

## 💡 Still Stuck?
If you have tried the steps above and are still blocked, open an **Issue** in this repository. When you do, please include:
1. A screenshot of the error.
2. A description of what you were trying to do.
3. The "Debug Route" steps you already tried.
