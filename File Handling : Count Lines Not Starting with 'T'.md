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
~~~
try:
    with open("story.txt", "r") as file:
        count = 0  
        
    
        for line in file:
        
            if line.strip() and not line.lstrip().startswith('T'):
                count +=1
    print("Number of lines that do NOT start with 'T':", count)

except FileNotFoundError:
    print("The file 'story.txt' was not found.")

~~~
## Output
![image](https://github.com/user-attachments/assets/81148fa8-351f-4a8a-b3b8-7b8a8fa2dfb9)

## Result
The python program is created and executed successfully.
