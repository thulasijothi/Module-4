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
d=eval(input())
print("Keys and Values sorted in alphabetical order by the key")
for key in sorted(d):
    print((key,d[key]),end=' ')

## Sample Output
![image](https://github.com/user-attachments/assets/4c2cc83b-15b8-43ca-8236-c982dfea293a)

## Result
This program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order
is successfully executed.
