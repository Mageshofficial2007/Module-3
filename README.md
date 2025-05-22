# 1.List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program:
```python
numbers = eval(input())
total = 0
for num in numbers:
    if num % 10 == 2:
        total += num
print("Sum=", total)
```
## Output:

![Screenshot 2025-05-22 081635](https://github.com/user-attachments/assets/0c7157ef-cc7e-4e10-a075-9df69188469b)

## Result:
Thus, the python program was executed successfully.


# 2.Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```
import re
l1 = []
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):
        l1.append(i)
print("Words without 'e':", l1)
```
## Output
![Screenshot 2025-04-29 120555](https://github.com/user-attachments/assets/441f2da3-ba81-472e-b7ce-d719b858935d)
## Result
Thus, the python program was executed successfully.


# 🧹3. Strings-Remove Nth Index Character from a String

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

# 4.Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```python
str1 = input()

result = str1[::-1]

if str1 == result:
    print("The entered string is palindrome")
else:
    print("The entered string is not palindrome")
```
## Output

![Screenshot 2025-05-22 083054](https://github.com/user-attachments/assets/cb8af950-67c4-4933-a6c7-45ea708f27a1)

## Result
Thus, the python program was executed successfully.

# 5.Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```python
tuple1=eval(input())
print('n' not in tuple1)
print('8' in tuple1)
```
## Output
![Screenshot 2025-05-22 083326](https://github.com/user-attachments/assets/8aacaa3d-5518-479b-8005-3a74de2ef004)

## Result
Thus, the python program was executed successfully.
