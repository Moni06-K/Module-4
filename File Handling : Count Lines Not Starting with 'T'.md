# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
count = 0

try:
    with open("story.txt", "r") as file:
        for line in file:
            if line.strip() and not line.startswith('T'):
                count += 1
    print(count)
except FileNotFoundError:
    print("story.txt file not found")
```
## Output
<img width="1485" height="581" alt="Screenshot 2026-06-04 235558" src="https://github.com/user-attachments/assets/a5868ab5-4985-45c5-9216-44c59ca0a685" />

## Result
Execution of program is completed.
