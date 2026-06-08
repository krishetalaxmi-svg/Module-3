# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

    items=[153,147,124,102]
    print(sum(items))

## Output
<img width="953" height="193" alt="image" src="https://github.com/user-attachments/assets/e720a1f7-d9e9-45bc-ba03-4579e3d8edfe" />

## Result
Thus the program executed successfully

# Regex in Python: Filter Words Without the Letter 'e'

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
      import re
      l1 = []
      items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
      for i in items:
          if not re.search(r"e", i):
              l1.append(i)
      print("Words without 'e':", l1)


## Output
<img width="532" height="161" alt="image" src="https://github.com/user-attachments/assets/8dc135f2-7e6b-47b0-bc2b-1f5722fb8820" />

## Result
Thus the program executed successfully
