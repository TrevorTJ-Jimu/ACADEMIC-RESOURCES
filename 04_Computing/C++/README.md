<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00599C,50:004482,100:0D2137&height=200&section=header&text=C%2B%2B%20Programming&fontSize=46&fontColor=ffffff&fontAlignY=40&desc=Systems%20Programming%20%7C%20OOP%20%7C%20Algorithms&descAlignY=60&descSize=17&descColor=b8d4ff&animation=fadeIn" />

[![Language](https://img.shields.io/badge/Language-C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)]()
[![Standard](https://img.shields.io/badge/Standard-C%2B%2B17-004482?style=for-the-badge)]()
[![Level](https://img.shields.io/badge/Level-Undergraduate-0D2137?style=for-the-badge)]()
[![Tutor](https://img.shields.io/badge/Tutor-Trevor%20Jimu-00599C?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TrevorTJ-Jimu)

<img src="https://media.giphy.com/media/ZVik7pIojeM0I9LUGl/giphy.gif" width="300" alt="coding C++"/>

> *"C++ is a language that trusts you completely — and gives you the power to match."*

</div>

---

## 📌 Module Overview

**C++ Programming** introduces students to one of the most powerful and widely used programming languages in existence. From **systems programming and game engines to embedded systems and scientific computing**, C++ forms the backbone of performance-critical software.

---

## 🗂️ Folder Contents

| Folder | Description |
|--------|-------------|
| 📄 `notes/` | Concept notes with annotated code examples |
| ✏️ `exercises/` | Coding challenges from beginner to advanced |
| 🚀 `projects/` | Mini projects demonstrating real-world application |

---

## 🧭 Topics Covered

### Chapter 1 — Foundations
- [ ] Setting Up: Compilers (GCC, Clang), IDEs (VS Code, Code::Blocks)
- [ ] Structure of a C++ Program
- [ ] Variables, Data Types & Constants
- [ ] Input/Output: `cin`, `cout`
- [ ] Operators & Expressions
- [ ] Type Casting

### Chapter 2 — Control Flow
- [ ] Conditional Statements: `if`, `else if`, `switch`
- [ ] Loops: `for`, `while`, `do-while`
- [ ] `break`, `continue`, `goto`

### Chapter 3 — Functions
- [ ] Function Declaration, Definition & Call
- [ ] Pass by Value vs Pass by Reference
- [ ] Default Arguments
- [ ] Function Overloading
- [ ] Recursion

### Chapter 4 — Arrays & Strings
- [ ] 1D and 2D Arrays
- [ ] C-style Strings vs `std::string`
- [ ] String Functions

### Chapter 5 — Pointers & Memory
- [ ] Pointer Basics: Declaration, Dereferencing
- [ ] Pointer Arithmetic
- [ ] Dynamic Memory: `new` and `delete`
- [ ] References vs Pointers

### Chapter 6 — Object-Oriented Programming
- [ ] Classes & Objects
- [ ] Constructors & Destructors
- [ ] Access Specifiers: `public`, `private`, `protected`
- [ ] Encapsulation, Abstraction
- [ ] Inheritance & Polymorphism
- [ ] Virtual Functions & Abstract Classes
- [ ] Operator Overloading

### Chapter 7 — STL & Advanced Topics
- [ ] Standard Template Library: `vector`, `map`, `set`, `stack`, `queue`
- [ ] Iterators & Algorithms (`sort`, `find`, `binary_search`)
- [ ] File I/O: `fstream`
- [ ] Exception Handling: `try`, `catch`, `throw`
- [ ] Templates: Function & Class Templates

---

## 💻 Hello World & Sample Code

```cpp
#include <iostream>
#include <vector>
#include <algorithm>
using namespace std;

// Function template example
template <typename T>
T findMax(vector<T>& arr) {
    return *max_element(arr.begin(), arr.end());
}

int main() {
    cout << "Hello, Trevor Jimu's C++ Resource!" << endl;

    vector<int> scores = {85, 92, 78, 96, 88};
    cout << "Highest score: " << findMax(scores) << endl;

    // Sort and display
    sort(scores.begin(), scores.end());
    cout << "Sorted scores: ";
    for (int s : scores) cout << s << " ";
    cout << endl;

    return 0;
}
```

---

## 🚀 Mini Projects

| Project | Concepts Covered |
|---------|-----------------|
| Student Grade Calculator | Arrays, Functions, Loops |
| Bank Account System | OOP, Classes, Encapsulation |
| Matrix Operations | 2D Arrays, Operator Overloading |
| Linked List Implementation | Pointers, Dynamic Memory |
| Simple File Database | File I/O, STL |

---

## 📬 Need Help?

[![Email](https://img.shields.io/badge/Email%20Trevor-jimtrevour%40gmail.com-00599C?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jimtrevour@gmail.com)

---

<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D2137,50:004482,100:00599C&height=100&section=footer" />

[![Back](https://img.shields.io/badge/←%20Computing-232526?style=for-the-badge)](../README.md)
</div>
