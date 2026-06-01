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
<img width="611" height="241" alt="Screenshot 2026-06-01 113042" src="https://github.com/user-attachments/assets/6b1d1c14-26fa-4b41-8033-ce2261b2d612" />


## Output
<img width="372" height="153" alt="Screenshot 2026-06-01 113052" src="https://github.com/user-attachments/assets/465ce6d6-2142-4cb8-9baa-5dbcb899b5d8" />

## Result
The execution of the program was successfully done.
