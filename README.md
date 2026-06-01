## Developed by: Mithun Kumar (212225040236 / 25012629)

# 1.List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

```
l = [1,2,3,44,5,6,7,8,9,1456]
s = sum(l)

print(f"Sum of the list {l} is {s}")
```
## Output
<img width="631" height="38" alt="image" src="https://github.com/user-attachments/assets/8fbf7eea-89ea-40b3-81c9-e7dbad208824" />

## Result
Thus the program has been executed successfully

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
    res = re.search(r"e",i)
    if res==None:
        l1.append(i)
        
print(f"Final list {l1}")

```
## Output
<img width="328" height="40" alt="image" src="https://github.com/user-attachments/assets/4d925ffc-86f6-498f-acfa-ef7ba5cf61f0" />

## Result
Thus the program has been executed successfully

# 3.🧹 Strings-Remove Nth Index Character from a String

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
```
def remove(s,n):
    if n>len(s): return s
    a = ''
    for i in range(len(s)):
        if i!=n:
            a+=s[i]
    return a

s = input('Enter the string: ')
n = int(input("Enter the index of that needs to removed: "))
print(f"Final word after removing character is \"{remove(s,n)}\"")
        
```
## Output
<img width="764" height="100" alt="image" src="https://github.com/user-attachments/assets/70a55f72-7b1c-44cc-940f-dd79e9529540" />

## Result
Thus the program has been executed successfully

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

```
s = 'google'
rev = s[::-1]

if s==rev:
    print("\"Google\" is a palindrome")
else:
    print("\"Google\" is not a palindrome")
```
## Output
<img width="362" height="33" alt="image" src="https://github.com/user-attachments/assets/a5d373b7-0f52-4eb8-a614-74402216bc7f" />

## Result
Thus the program has been executed successfully

# 5.Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
  ```
tup = (1,45,'nin',5,2,'a',123,'Saveetha','SEC','lol','3')

print(f"\'n\' in tup = {'n' in tup}")
print(f"8 in tup = {8 in tup}")
```
## Output
<img width="256" height="56" alt="image" src="https://github.com/user-attachments/assets/93d8f33b-4510-4f9f-8049-385d8774c230" />

## Result
Thus the program has been executed successfully
