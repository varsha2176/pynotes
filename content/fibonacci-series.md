---
title: Fibonacci-Series
date: 2025-06-21
author: Your Name
cell_count: 2
score: 0
---

This notebook prints the Fibonacci series up to N terms.


```python
n = int(input("How many terms? "))
a, b = 0, 1
print("Fibonacci sequence:")
for _ in range(n):
    print(a, end=' ')
    a, b = b, a + b

```


---
**Score: 0**