# Arithmetic Operations Using Multiple Inheritance in Python

This Python program demonstrates **multiple inheritance** by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes.

## 🎯 Aim

To write a Python program to calculate **Add, Sub & Division** using **Multiple Inheritance**.

## 🧠 Algorithm

1. **Define `Calculation1` class**
   - Contains `Summation(a, b)` method to return the sum of two numbers.
2. **Define `Calculation2` class**
   - Contains `Subtraction(a, b)` method to return the difference of two numbers.
3. **Define `Derived` class**
   - Inherits from both `Calculation1` and `Calculation2`.
   - Contains `Division(a, b)` method to return the division result.
4. **Input**
   - Prompt the user to enter two numbers.
5. **Process**
   - Create an object of the `Derived` class.
   - Call `Summation`, `Subtraction`, and `Division` methods.
6. **Output**
   - Display the results of the three operations.

## 💻 Program 
```
class value:
    def __init__(self,a,b):
        self.a=a
        self.b=b
class division(value):
    def add(self):
        
        print(self.a+self.b)
    def sub(self):
        print(self.a - self.b)
    def div(self):
        print(self.a/self.b)
a=int(input())
b=int(input())
c=division(a,b)
c.add()
c.sub()
c.div()
```
## Output Example
<img width="413" height="207" alt="{E09AD96A-16DD-41B8-B579-7E284E78DF0D}" src="https://github.com/user-attachments/assets/96e992ab-fd73-400c-9ae1-2ac2a145d1be" />
##Result
Thus,the program is executed successfully.
