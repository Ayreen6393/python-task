# python-task
This repository Contains two Python Script
# Task - 1 Basic Arithmetic Operations

**Functionality**:
- Takes two numbers from the user as input.
- Performs the following operations:
  - Addition
  - Subtraction
  - Multiplication
  - Division (with zero-division handling)
- Displays the results of all operations.

**How to run**:

python task1.py

a = input("Enter num1 : ")
a = float(a)
b = input("Enter num2 : ")
b = float(b)
print("Addition : ",a+b)
print("Subtraction : ",a-b)
print("Multiplication : ",a*b)
print("Division : ",a/b)

# Task-2 Greeting with Full Name

**Functionality**:
- Takes the user's first and last name as input.
- Combines them into a full name.
- Displays a personalized greeting message using the full name.

**How to run**:

python task2.py

fname = input("Enter your first name : ")
lname = input("Enter your last name : ")
print("First name :",fname)
print("Last name :",lname,"\n")
print("Hello",fname+lname,"! Welcome to Python Project")
