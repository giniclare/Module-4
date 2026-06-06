# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1 = [10, 20, 30]

try:
    print(list1[5])
except IndexError:
    print("You're out of list range")
```

## Output
<img width="404" height="120" alt="image" src="https://github.com/user-attachments/assets/5258a2cb-44b7-40f4-b584-68caa41c222d" />

## Result
Thus, the Python program to handle an IndexError using a try-except block was successfully executed, and the appropriate error message was displayed when an index beyond the list range was accessed.

