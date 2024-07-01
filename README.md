[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15354866&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
Definition: Python is a high-level, interpreted programming language known for its simplicity and readability.
Key Features: Readable syntax, extensive standard library, dynamically typed, and cross-platform compatibility.
Popular Use Cases: Web development (Django, Flask), data analysis/machine learning (NumPy, Pandas, TensorFlow), automation/scripting.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
Steps:
Download Python from python.org.
Install using the downloaded installer.
Verify installation with python --version.
Set up a virtual environment (optional but recommended).
3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
Example:
print("Hello, World!")
Basic Elements: print() function, string literal "Hello, World!".


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
Data Types: Integer (int), float (float), string (str), boolean (bool).
Example:
a = 10          # integer
b = 3.14        # float
c = "Python"    # string
d = True        # boolean


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
Conditional Statements: if-else.
Loops: for.
Examples:
x = 10
if x > 5:
    print("x is greater than 5")
else:
    print("x is 5 or less")

for i in range(5):
    print(i)

    
6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
Definition: Reusable blocks of code.
Example:
def sum_two_numbers(a, b):
    return a + b

result = sum_two_numbers(3, 5)
print("Sum:", result)



7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
Lists (list): Ordered collection. Dictionaries (dict): Unordered key-value pairs.
Example:
numbers = [1, 2, 3, 4, 5]
person = {'name': 'Alice', 'age': 30, 'city': 'New York'}

numbers.append(6)
person['job'] = 'Engineer'

for num in numbers:
    print(num)

for key, value in person.items():
    print(key, ":", value)
    
8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
Purpose: Manage errors gracefully during execution.
Example:
try:
    x = 1 / 0  # Raises ZeroDivisionError
except ZeroDivisionError:
    print("Cannot divide by zero!")
finally:
    print("Execution completed.")


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
Modules: Python files containing definitions.
Packages: Directories of modules with an __init__.py file.
Example:
python
Copy code
import math
print(math.sqrt(16))  # prints 4.0


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
Reading: open() function with 'r' mode.
Writing: open() function with 'w' mode.
Examples:
with open('file.txt', 'r') as f:
    content = f.read()
    print(content)
data = ["apple", "banana", "cherry"]
with open('output.txt', 'w') as f:
    for item in data:
        f.write(item + '\n')
# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


