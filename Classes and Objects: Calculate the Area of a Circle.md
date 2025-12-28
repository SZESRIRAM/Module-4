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
```
class cse:
    def mech(x, r):
        area = 3.1416 * r * r
        print(f"Area of circle: {area:.2f}")
obj = cse()
radius = float(input())
obj.mech(radius)
```
## Output
<img width="633" height="145" alt="image" src="https://github.com/user-attachments/assets/d6d0f682-d721-4f7c-aa14-a6f701cbd38c" />

## Result
Thus, the given program has been executed successfully and the area of the circle is calculated using classes and objects in Python.
