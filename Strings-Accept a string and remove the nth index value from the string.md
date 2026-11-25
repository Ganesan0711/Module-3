
# 🧹 Strings: Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove()` that takes a string as an argument.
2. Read the index `n` from the user.
3. Initialize an empty string `a` to store the modified string.
4. Iterate through each character using a `for` loop.
5. Check whether the current index `i` is not equal to `n`.
6. If `i != n`, append the character to string `a`.
7. Return the modified string.
8. Print the final result.

## 💻 Program

```python
def remove(string):
    n = int(input("Enter the index to remove: "))
    a = ""

    for i in range(len(string)):
        if i != n:
            a += string[i]

    return a


string = input("Enter a string: ")
print("String after removing character:", remove(string))
```

## 📤 Output

```text
Enter a string: Python
Enter the index to remove: 2
String after removing character: Pyhon
```

## ✅ Result
Thus, the Python program to remove a character at the specified index from a string was executed successfully.
