# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```python
def remove(s):
    result = ""
    i = 0
    for char in s:
        if i != n:
            result += char
        i += 1
    print(result)
n=int(input())
```

## Output

![Screenshot 2025-05-22 082646](https://github.com/user-attachments/assets/4ae317f3-891b-4685-ba38-9150ea782ce7)

## Result
Thus, the python program was executed successfully.
