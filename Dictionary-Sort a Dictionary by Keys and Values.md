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
~~~
my_dict = {
    'banana': 'yellow',
    'apple': 'red',
    'grape': 'purple',
    'cherry': 'red',
    'blueberry': 'blue'
}

sorted_by_keys = dict(sorted(my_dict.items()))

sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))

print("Original Dictionary:")
print(my_dict)

print("\nDictionary Sorted by Keys:")
print(sorted_by_keys)

print("\nDictionary Sorted by Values:")
print(sorted_by_values)
~~~

## Sample Output
![image](https://github.com/user-attachments/assets/0dbc229e-6002-41f6-a7a8-7be6386e19f8)

## Result
The python program is created and executed successfully.
