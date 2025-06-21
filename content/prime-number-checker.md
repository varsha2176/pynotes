---
title: Prime-Number-Checker
date: 2025-06-21
author: Your Name
cell_count: 3
score: 0
---

This notebook checks if a given number is prime.


```python
def is_prime(n):
    if n <= 1:
        return False
    for i in range(2, int(n ** 0.5)+1):
        if n % i == 0:
            return False
    return True

num = int(input("Enter a number: "))
if is_prime(num):
    print(f"{num} is a Prime number!")
else:
    print(f"{num} is not a Prime number.")

```

    Enter a number:  7
    

    7 is a Prime number!
    


```python

```


---
**Score: 0**