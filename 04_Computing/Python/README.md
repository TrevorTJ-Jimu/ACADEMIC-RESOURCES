<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:3776AB,50:FFD43B,100:306998&height=200&section=header&text=Python%20Programming&fontSize=44&fontColor=ffffff&fontAlignY=40&desc=Clean%20Code%20%7C%20Data%20Science%20%7C%20Automation&descAlignY=60&descSize=17&descColor=fffbd0&animation=fadeIn" />

[![Language](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=FFD43B)]()
[![Level](https://img.shields.io/badge/Level-Undergraduate-306998?style=for-the-badge)]()
[![Tutor](https://img.shields.io/badge/Tutor-Trevor%20Jimu-3776AB?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TrevorTJ-Jimu)

<img src="https://media.giphy.com/media/coxQHKASG60HrHtvkt/giphy.gif" width="300" alt="python coding"/>

> *"Python is not just a programming language — it's the most readable way to turn ideas into running code."*

</div>

---

## 📌 Module Overview

**Python Programming** introduces one of the world's most popular and versatile languages. Python's clean syntax makes it ideal for beginners, while its rich ecosystem of libraries — **NumPy, Pandas, Matplotlib, SciPy** — makes it the dominant tool in **data science, scientific computing, and automation**.

---

## 🗂️ Folder Contents

| Folder | Description |
|--------|-------------|
| 📄 `notes/` | Concept explanations with runnable code |
| ✏️ `exercises/` | Graded coding problems |
| 🚀 `projects/` | Applied mini-projects |

---

## 🧭 Topics Covered

### Chapter 1 — Python Fundamentals
- [ ] Installation: Python, pip, VS Code / Jupyter
- [ ] Variables, Data Types: `int`, `float`, `str`, `bool`
- [ ] Operators & Expressions
- [ ] Input & Output: `input()`, `print()`
- [ ] Type Conversion

### Chapter 2 — Control Flow
- [ ] `if`, `elif`, `else`
- [ ] `for` loops, `while` loops
- [ ] `break`, `continue`, `pass`
- [ ] List Comprehensions

### Chapter 3 — Data Structures
- [ ] Lists, Tuples, Sets
- [ ] Dictionaries
- [ ] Strings & String Methods
- [ ] Nested Structures

### Chapter 4 — Functions
- [ ] Defining & Calling Functions
- [ ] Arguments: Positional, Keyword, Default, *args, **kwargs
- [ ] Lambda Functions
- [ ] Scope & Closures
- [ ] Recursion

### Chapter 5 — Object-Oriented Python
- [ ] Classes & Objects
- [ ] `__init__`, Instance Methods
- [ ] Inheritance & Polymorphism
- [ ] Magic/Dunder Methods
- [ ] Encapsulation

### Chapter 6 — File Handling & Exceptions
- [ ] Reading & Writing Files
- [ ] CSV & JSON handling
- [ ] `try`, `except`, `finally`
- [ ] Custom Exceptions

### Chapter 7 — Scientific Computing & Data
- [ ] **NumPy**: arrays, broadcasting, linear algebra
- [ ] **Pandas**: DataFrames, cleaning, groupby, merge
- [ ] **Matplotlib & Seaborn**: plotting and visualisation
- [ ] **SciPy**: statistical functions and scientific tools
- [ ] Introduction to **Jupyter Notebooks**

---

## 💻 Sample Code

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

# --- Data Analysis Example ---
data = {
    'Student': ['Alice', 'Bob', 'Carol', 'David', 'Eve'],
    'Score':   [85, 92, 78, 96, 88],
    'Grade':   ['B', 'A', 'C', 'A', 'B']
}

df = pd.DataFrame(data)
print(df.describe())

# Statistics
print(f"Mean Score:   {df['Score'].mean():.2f}")
print(f"Std Dev:      {df['Score'].std():.2f}")
print(f"Top Student:  {df.loc[df['Score'].idxmax(), 'Student']}")

# Visualisation
df.plot(kind='bar', x='Student', y='Score',
        color='steelblue', title='Student Scores')
plt.tight_layout()
plt.savefig('scores.png')
plt.show()
```

---

## 🚀 Mini Projects

| Project | Libraries Used |
|---------|---------------|
| Student Report Generator | pandas, openpyxl |
| Statistical Calculator | numpy, scipy |
| Grade Distribution Visualiser | matplotlib, seaborn |
| CSV Data Cleaner | pandas |
| Simple CLI Quiz App | random, json |

---

## 📬 Need Help?

[![Email](https://img.shields.io/badge/Email%20Trevor-jimtrevour%40gmail.com-3776AB?style=for-the-badge&logo=gmail&logoColor=FFD43B)](mailto:jimtrevour@gmail.com)

---

<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:FFD43B,50:3776AB,100:306998&height=100&section=footer" />

[![Back](https://img.shields.io/badge/←%20Computing-232526?style=for-the-badge)](../README.md)
</div>
