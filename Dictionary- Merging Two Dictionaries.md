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
def merge(dict1,dict2):
     merged_dict = {**dict1, **dict2}
     return merged_dict
dict1 = {'a': 10, 'b': 20, 'c': 30}
dict2 = {'b': 25, 'd': 40}
merge(dict1,dict2)
    
```

## Output
<img width="410" height="75" alt="image" src="https://github.com/user-attachments/assets/c574cbc5-f520-447e-8a48-0012680cfbaf" />


## Result
the code executed successfully
