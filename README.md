# 1. List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
<img width="452" height="124" alt="Screenshot 2026-06-01 105608" src="https://github.com/user-attachments/assets/148fe552-b0e4-4b26-ae03-25fe54ce049e" />


## Output
<img width="373" height="147" alt="Screenshot 2026-06-01 105631" src="https://github.com/user-attachments/assets/b88bda3d-4dc4-4f37-a402-3f4352bdefa0" />


## Result
The execution of the program was successfully done.

# 2. Regex in Python: Filter Words Without the Letter 'e'

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


#  3. Strings-Remove Nth Index Character from a String

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
<img width="553" height="313" alt="Screenshot 2026-06-01 113449" src="https://github.com/user-attachments/assets/f0a003d0-b89c-477e-8f4f-4fbf926da44e" />


## Output
<img width="407" height="193" alt="Screenshot 2026-06-01 113456" src="https://github.com/user-attachments/assets/ec925ead-2f34-4076-9231-ba30f91c183a" />


## Result
The execution of the program was successfully done.

# 4. Strings-Palindrome Check in Python (Without Built-in Functions)

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
<img width="557" height="209" alt="Screenshot 2026-06-01 113931" src="https://github.com/user-attachments/assets/da74bf83-2ffd-4890-84b7-e24d99e16293" />


## Output
<img width="406" height="164" alt="Screenshot 2026-06-01 113938" src="https://github.com/user-attachments/assets/36f3e790-5129-4a09-b82d-cbafba3dbbe8" />


## Result
The execution of the program was successfully done.
