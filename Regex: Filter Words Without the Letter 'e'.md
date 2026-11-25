
# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program using regular expressions (regex) to filter and return all elements from a list that do not contain the letter 'e'.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store the results.
3. Define a list of words:
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list.
5. Use `re.search(r"e", i)` to check whether the word contains the letter 'e'.
6. If the letter 'e' is not present, append the word to `l1`.
7. Print the filtered list.

## 🧾 Program

```python
import re

items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']

l1 = []

for i in items:
    if not re.search(r"e", i):
        l1.append(i)

print("Words without the letter 'e':", l1)
```

## 💻 Output

```text
Words without the letter 'e': ['goal', 'sit']
```

## ✅ Result
Thus, the Python program to filter words that do not contain the letter 'e' using regular expressions was executed successfully.
