# Hierarchical Inheritance in Python

This Python project demonstrates **Hierarchical Inheritance** using a base class `Details` and two derived classes `Employee` and `Patient`. The program collects and displays details for both employees and patients.

## 🎯 Aim

To write a Python program that uses **Hierarchical Inheritance** to input and display **Employee** and **Patient** details.

## 📘 Description

- **Base Class:** `Details`
  - Stores common attributes: `name`, `age`
  - Provides methods: `getName()`, `getAge()`

- **Derived Class 1:** `Employee`
  - Inherits from `Details`
  - Adds: `employee_id`, `department`
  - Method: `getEmployeeDetails()`

- **Derived Class 2:** `Patient`
  - Inherits from `Details`
  - Adds: `patient_id`, `disease`
  - Method: `getPatientDetails()`

## 🧠 Algorithm

1. Create base class `Details` with common attributes.
2. Create `Employee` class extending `Details`, adding employee-specific data.
3. Create `Patient` class extending `Details`, adding patient-specific data.
4. Get user input for employee and patient data.
5. Display collected information using class methods.

## Program
```
class Details:
    def __init__(self, id, name, gender):
        self.id = id
        self.name = name
        self.gender = gender

    def display_basic(self):
        print("Id: ", self.id)
        print("Name: ", self.name)
        print("Gender: ", self.gender)


# Child class Employee
class Employee(Details):
    def __init__(self, id, name, gender, company, department):
        super().__init__(id, name, gender)
        self.company = company
        self.department = department

    def display(self):
        print("Employee Object")
        self.display_basic()
        print("Company: ", self.company)
        print("Department: ", self.department)
        print()


# Child class Doctor
class Doctor(Details):
    def __init__(self, id, name, gender, hospital, department):
        super().__init__(id, name, gender)
        self.hospital = hospital
        self.department = department

    def display(self):
        print("Doctor Object")
        self.display_basic()
        print("Hospital: ", self.hospital)
        print("Department: ", self.department)


# ---- Input for Employee ----
id1 = int(input())
name1 = input()
gender1 = input()
company = input()
dept1 = input()

# ---- Input for Doctor ----
id2 = int(input())
name2 = input()
gender2 = input()
hospital = input()
dept2 = input()

# ---- Object Creation ----
emp = Employee(id1, name1, gender1, company, dept1)
doc = Doctor(id2, name2, gender2, hospital, dept2)

# ---- Display ----
emp.display()
doc.display()
```
## Sample Output
<img width="653" height="462" alt="{A50B0DF1-DED1-4927-820A-4A5CF82FE7BE}" src="https://github.com/user-attachments/assets/38efebb7-a5e5-4cbe-bd87-454056c443cc" />

