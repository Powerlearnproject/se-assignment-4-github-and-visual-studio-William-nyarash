[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15439249&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   Python is a high-level, interpreted, and general-purpose dynamic programming language. It's known for its readability and simplicity. It's widely used in scientific computing, data analysis, machine learning, web development, and automation.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   Update package lists for upgrades and new package installations: Open your terminal and run sudo apt update.

Install Python: Run sudo apt install python3. To verify the installation, use python3 --version.

Install pip: Python's package installer pip is often needed. Install it using sudo apt install python3-pip. Verify with pip3 --version.

Verify Python version: You can check your Python version with python3 -V.

- Set up a virtual `environment`: A virtual `environment` is a tool that helps to keep dependencies required by different projects separate by creating isolated Python environments for them. 
- Install `virtualenv` using `pip` with `sudo pip3 install virtualenv`.
-  To create a virtual environment, use ` virtualenv myenv`.
-  To activate it, run `source myenv/bin/activate`.
-  You'll see (myenv) before your prompt, indicating that the `virtual environment` is `active`.

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

```bash
print("Hello world!")
```


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   It uses the print() function to output "Hello, World!" to the console.

Python's basic data types include int (integers), float (floating-point numbers), str (strings), bool (booleans), and list (ordered, mutable sequences). Here's a script demonstrating variables:

```bash
a = 5
b = 2.5
c = "Hello"
d = False
e = [1,2,3,4,5]
```

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   Python uses conditional statements and loops for control structures. Here's an example of an if-else statement and a for loop:

   ```bash
   if a > 0:
    print("Positive")
else:
    print("Non-positive")

for i in range(5):
    print(i)
   ```

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   Functions in Python are blocks of reusable code. Here's a function that takes two arguments and returns their sum:

   ```bash
   def add(x, y):
    return x + y

   print(add(3, 4))
   ```

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.


Lists and dictionaries are compound data types. Lists are ordered collections of items, while dictionaries are unordered collections of key-value pairs. Here's a script demonstrating both:

```bash
letters = [a,b,c,d,e,f]
```

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.


Exception Handling: Exception handling in Python is a mechanism to handle exceptions or errors during the execution of a program. It allows the program to continue running instead of crashing.

```python
try:
    # code block where an exception can occur
    x = 10 / 0
except ZeroDivisionError as e:
    # code block to handle the exception
    print("You can't divide by zero!")
finally:
    # code block that runs no matter what
    print("This will always run.")
    
```

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   Modules and Packages: Modules are Python files with a .py extension. They allow code reusability. Packages are directories containing modules. To import a module, use import module_name. 
   ```python
      import math 
      #import the math module

      print(math.sqrt(16))

   #output 4.0
   ```

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.


    File I/O: To read from a file, use open(file_name, 'r'). Then, use read() to read the content. To write to a file, open it in write mode ('w') and use write(). 

    ```python
      with open('file.txt') as file:
         content = file.read()

      print(content)
    ```

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


