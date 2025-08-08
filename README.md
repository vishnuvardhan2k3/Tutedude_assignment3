# 🧮 Python Math Tasks

This repository contains two simple Python scripts that demonstrate:
- Recursive function usage (`factorial`)
- Common mathematical operations using Python's built-in `math` module

---

## 📌 Task 1: Factorial Using Recursion

### 🔧 Description:
A recursive function is used to calculate the factorial of a given number.

### 🧠 Logic:
The factorial of a number `n` is computed recursively:
```python
def factorial(n):
    global res
    if(n == 1):
        return 1
    return n * factorial(n - 1)

print(factorial(5))
```

## 📌 Task 2: Math Module Operations

### 🔧 Description:
This task demonstrates the use of Python's built-in `math` module to perform basic mathematical operations on a user-provided input.

### 🧠 Logic:
The script takes an integer input and computes:
- ✅ Square root of the number
- ✅ Natural logarithm (base e)
- ✅ Sine of the number (interpreted in radians)

### 💻 Code:
```python
import math

n = int(input())
print(math.sqrt(n))
print(math.log(n))
print(math.sin(n))
