## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```
dict1 = {'a': 1, 'b': 2}
dict2 = {'c': 3, 'd': 4}

def merge():
    return {**dict1, **dict2}

print(merge())
```

## Output
<img width="374" height="117" alt="image" src="https://github.com/user-attachments/assets/3e303aef-55f8-41df-b90d-fa2103df2e97" />

## Result
Thus, the Python program to merge two dictionaries and combine their key-value pairs using the ** unpacking operator was successfully executed, and the desired output was obtained.
