---
title: Leap-Year-Checker
date: 2025-06-21
author: Your Name
cell_count: 2
score: 0
---

This notebook checks whether a year is a leap year or not.


```python
def is_leap_year(year):
    if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
        return True
    return False

year = int(input("Enter a year: "))
if is_leap_year(year):
    print(f"{year} is a leap year!")
else:
    print(f"{year} is not a leap year.")

```


---
**Score: 0**