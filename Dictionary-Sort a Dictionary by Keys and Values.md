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
d = {
    'banana': 3,
    'apple': 1,
    'orange': 2
}

print("Original Dictionary:", d)

sorted_keys = dict(sorted(d.items()))
print("Sorted by Keys:", sorted_keys)

sorted_values = dict(sorted(d.items(), key=lambda item: item[1]))
print("Sorted by Values:", sorted_values)
```

## Output
<img width="447" height="257" alt="image" src="https://github.com/user-attachments/assets/d5591ee6-eae2-4ebb-8ae8-353b86465415" />

## Result

Thus, the Python program to sort a dictionary alphabetically by keys and values was successfully executed, and the desired output was obtained.

