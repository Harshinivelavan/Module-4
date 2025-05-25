# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
~~~
import math
class cse:
    def mech(self, radius):
        area = math.pi * (radius ** 2)
        return area
try:
    radius_input = float(input())
    
    obj = cse()
    result = obj.mech(radius_input)
    
    print(f"The area of the circle with radius {radius_input} is: {result:.2f}")
except ValueError:
    print("Please enter a valid number for the radius.")
~~~
## Output
![image](https://github.com/user-attachments/assets/0b332703-72fc-4c42-9542-f479cb252774)

## Result
The python program is created and executed successfully.
