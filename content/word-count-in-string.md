---
title: Word-Count-In-String
date: 2025-06-21
author: Your Name
cell_count: 3
score: 0
---

Count the frequency of each word in a sentence.


```python
text = input("Enter a sentence: ").lower()
words = text.split()
word_count = {}

for word in words:
    word_count[word] = word_count.get(word, 0) + 1

print("Word Frequencies:")
for word, count in word_count.items():
    print(f"{word}: {count}")

```

    Enter a sentence:  aruna varsha
    

    Word Frequencies:
    aruna: 1
    varsha: 1
    


```python

```


---
**Score: 0**