# Multilevel Inheritance Example in Python

This Python project demonstrates the concept of **Multilevel Inheritance** to collect and display the **name**, **age**, and **location** of a person.

## 🎯 Aim

To write a Python program that uses multilevel inheritance to get and display a person’s name, age, and location.

## 🧠 Algorithm

1. **Parent Class**  
   - `__init__(name)` initializes the `name` attribute.  
   - `getName()` returns the `name`.

2. **Child Class (inherits Parent)**  
   - `__init__(name, age)` initializes `name` using `super()` and adds `age`.  
   - `getAge()` returns the `age`.

3. **Grandchild Class (inherits Child)**  
   - `__init__(name, age, location)` initializes `name` and `age` using `super()` and adds `location`.  
   - `getLocation()` returns the `location`.

4. **Input & Output**  
   - Take user input for name, age, and location.  
   - Create an instance of `Grandchild`.  
   - Print all details using class methods.

## Program
```
class name:
    def get_name(self):
        self.name=name
class age(name):
    def get_age(self):
        self.age=age
class Id(age):
    def get_id(self):
        self.id=id
    def display(self):
        print(name,age,id)
name=input()
age=int(input())
id=input()
c=Id()
c.get_name()
c.get_age()
c.get_id
c.display()
```

## Sample Output
<img width="685" height="215" alt="{D9AC1F81-A59E-4981-8027-382764F16555}" src="https://github.com/user-attachments/assets/5cb639d4-065e-4cc6-af86-d2bfbaf1298a" />
## Result
Thus,the program is executed successfully.
