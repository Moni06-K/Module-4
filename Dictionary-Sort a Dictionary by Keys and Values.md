# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
# Original Dictionary
d = {'c': 'cat', 'a': 'apple', 'b': 'ball', 'd': 'dog'}

# Sort by Keys
sorted_keys = dict(sorted(d.items()))

# Sort by Values
sorted_values = dict(sorted(d.items(), key=lambda item: item[1]))

print("Original Dictionary:", d)
print("Dictionary Sorted by Keys:", sorted_keys)
print("Dictionary Sorted by Values:", sorted_values)
```

## Sample Output
<img width="1740" height="649" alt="Screenshot 2026-06-03 111927" src="https://github.com/user-attachments/assets/d491cc1f-806b-4373-ae5e-42dd76742ff5" />

## Result

Execution of program is completed
