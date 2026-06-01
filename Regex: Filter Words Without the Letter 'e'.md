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
