# SE-Assignment-6
 Assignment: Introduction to Python
What is Python?
Python is a high-level, interpreted programming language known for its simplicity and readability. It was created by Guido van Rossum and first released in 1991. Python's key features include:

Readability: Python's syntax is clean and easy to understand.
Versatility: Python can be used for web development, data analysis, artificial intelligence, scientific computing, automation, and more.
Extensive Libraries: Python has a rich ecosystem of libraries and frameworks such as NumPy, Pandas, Django, Flask, and TensorFlow.
Community Support: Python has a large and active community that contributes to its development and provides extensive resources for learning and troubleshooting.

Use Cases
Web Development: Using frameworks like Django and Flask.
Data Science and Machine Learning: Utilizing libraries like Pandas, NumPy
Automation and Scripting: Writing scripts for automating repetitive tasks.
Scientific Computing: Using libraries like SciPy for complex computations.

Steps to Install Python
Windows
Download: Go to the Python website and download the latest version for Windows.
Install: Run the installer and check the option to add Python to the PATH.
Verify: Open Command Prompt and type python --version to verify the installation.
macOS
Download: Go to the Python website and download the latest version for macOS.
Install: Run the downloaded installer.
Verify: Open Terminal and type python3 --version to verify the installation.
Linux
Install: Open Terminal and run:
sudo apt-get update
sudo apt-get install python3
Verify: Type python3 --version in Terminal to verify the installation.

Setting Up a Virtual Environment
Create Virtual Environment:
python3 -m venv myenv

Activate Virtual Environment:
Windows:
myenv\Scripts\activate

macOS/Linux:
source myenv/bin/activate

Python Syntax and Semantics
Hello, World! Program
print("Hello, World!")
print: A built-in function that outputs text to the console.
"Hello, World!": A string literal enclosed in double quotes.

Data Types and Variables
Basic Data Types
int: Integer (e.g., 42)
float: Floating-point number (e.g., 3.14)
str: String (e.g., "Python")
bool: Boolean (e.g., True or False)
Example Script
# Integer
age = 25

# Float
price = 19.99

# String
name = "Alice"

# Boolean
is_student = True

print(f"Name: {name}, Age: {age}, Price: ${price}, Is Student: {is_student}")

Control Structures
Conditional Statements
age = 18
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
    
Loops
# For Loop
for i in range(5):
    print(i)

# While Loop
count = 0
while count < 5:
    print(count)
    count += 1
    
Functions in Python
Functions are reusable blocks of code that perform a specific task. They help in organizing and modularizing code.

Example Function

def add(a, b):
    return a + b

# Calling the function
result = add(10, 5)
print(f"Sum: {result}")

Lists and Dictionaries
Lists
Lists are ordered collections of items.


numbers = [1, 2, 3, 4, 5]
numbers.append(6)
print(numbers)

Dictionaries
Dictionaries are collections of key-value pairs.


student = {"name": "Alice", "age": 25, "is_student": True}
print(student["name"])

Exception Handling
Exception handling allows you to manage errors gracefully without crashing the program.


try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero.")
finally:
    print("This block is executed no matter what.")
Modules and Packages
Concepts
Modules: Single Python files containing functions and classes.
Packages: Directories of Python modules.
Using a Module

import math

print(math.sqrt(16))
File I/O

Reading from a File
with open("example.txt", "r") as file:
    content = file.read()
    print(content)
    
Writing to a File
data = ["line 1", "line 2", "line 3"]
with open("output.txt", "w") as file:
    for line in data:
        file.write(line + "\n")



