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
a=eval(input())
b=sorted(a.items())
print("Keys and Values sorted in alphabetical order by the key")
for i,j in b:
    print(f"({i}, {j})",end=" ")
```

## Sample Output
<img width="356" height="126" alt="image" src="https://github.com/user-attachments/assets/f5cb88ba-44f4-4ef6-a65e-ef416b96b008" />
<img width="560" height="122" alt="image" src="https://github.com/user-attachments/assets/28f63d91-1c4d-4c64-8396-21b77b701262" />


## Result
Thus, the given program has been executed successfully and the dictionary is sorted alphabetically by keys.

