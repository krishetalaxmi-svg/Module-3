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
    n=int(input())
    def remove(a):
        for i in range(0,len(a)):
            if(i!=n):
                print(a[i],end='')

## Output
<img width="1190" height="302" alt="image" src="https://github.com/user-attachments/assets/cb5d8370-887d-4b61-9da7-90e6a0a48f4c" />

## Result
Thus the program executed successfully
