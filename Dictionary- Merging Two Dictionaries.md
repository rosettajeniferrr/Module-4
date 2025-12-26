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
dict1=eval(input())
dict2=eval(input())
print({**dict1 , **dict2})
```
## Output
<img width="1058" height="240" alt="image" src="https://github.com/user-attachments/assets/4746138f-82aa-41d7-bd84-a44f962fce14" />

## Result
Thus, the program has been successfully executed.
