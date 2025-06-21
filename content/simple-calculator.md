---
title: Simple-Calculator
date: 2025-06-21
author: Your Name
cell_count: 3
score: 0
---

A basic calculator that supports +, -, *, /


```python
def calculator(a, b, op):
    if op == '+':
        return a + b
    elif op == '-':
        return a - b
    elif op == '*':
        return a * b
    elif op == '/':
        return a / b if b != 0 else "Error: Division by zero"
    else:
        return "Invalid operator"

a = float(input("Enter first number: "))
b = float(input("Enter second number: "))
op = input("Enter operator (+, -, *, /): ")

print("Result:", calculator(a, b, op))

```

    Enter first number:  5
    Enter second number:  9
    Enter operator (+, -, *, /):  -
    

    Result: -4.0
    


```python

```


---
**Score: 0**