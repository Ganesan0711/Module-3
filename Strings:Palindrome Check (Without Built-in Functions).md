
# Strings: Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string "google" is a palindrome or not without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string "google" to a variable.
2. Reverse the string manually using slicing `[::-1]`.
3. Compare the original string with the reversed string.
4. If both strings are equal, print "Palindrome".
5. Otherwise, print "Not a Palindrome".
6. Execute the program.

## 🧾 Program

```python
string = "google"

reverse = string[::-1]

if string == reverse:
    print("The string is a palindrome")
else:
    print("The string is not a palindrome")
```

## 💻 Output

```text
The string is not a palindrome
```

## ✅ Result
Thus, the Python program to check whether the given string is a palindrome or not using string slicing was executed successfully.
