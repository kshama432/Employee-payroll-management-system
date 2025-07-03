 Employee Payroll Management System

## 📌 Project Overview

The **Employee Payroll Management System** is a simple Java-based console application that demonstrates the use of **Object-Oriented Programming (OOP)** principles such as **abstraction, inheritance, encapsulation, and polymorphism**. This project allows you to manage employee records (full-time and part-time), calculate their salaries, and perform basic operations like add, remove, and display employee information.

---

## 🛠️ Technologies Used

- Java
- OOP Concepts
- ArrayList (Java Collections)

- ## 🚀 Features

- Add Full-Time and Part-Time Employees
- Calculate salary based on employment type
- Remove employee by ID
- Display all employees with details
- Dynamic employee list management using ArrayList

- ## 🔑 OOP Concepts Used

| Concept         | Implementation                                                                 |
|----------------|----------------------------------------------------------------------------------|
| Abstraction     | `Employee` abstract class with abstract method `calculateSalary()`              |
| Inheritance     | `FullTimeEmployee` and `PartTimeEmployee` extend `Employee`                     |
| Polymorphism    | Method overriding for salary calculation                                        |
| Encapsulation   | Private fields with public getter methods     

EmployeePayrollSystem/
│
├── Main.java
├── Employee.java
├── FullTimeEmployee.java
├── PartTimeEmployee.java
├── PayrollSystem.java

#output.........
Initial Employee Details:
Employee [name=kshama,id=1, salary=70000.0]
Employee [name=jaya,id=2, salary=4000000.0]

Removing employees
Remaining Employees Details:
Employee [name=kshama,id=1, salary=70000.0]
