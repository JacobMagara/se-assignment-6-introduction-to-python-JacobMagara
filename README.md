[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15305655&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

Python is a popular high-level programming language known for its simplicity, readability, and versatility. Key features include its clear syntax, extensive standard library, and active community support. Python is widely used in:
      1. Scientific Computing: Tools like SciPy support scientific computations and simulations.
      2. Data Science and Machine Learning: Libraries such as NumPy, Pandas, and TensorFlow make Python essential for data analysis and machine learning applications.
      3. Web Development: Frameworks like Django and Flask enable rapid development of websites and APIs.


2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
Installing Python on Windows:
   1. Download the latest Python installer for Windows (.exe file)
   2. Double-click the downloaded .exe file and ensure to select "Add Python x.x to PATH" during installation.
   3. Open Command Prompt or PowerShell and type python --version to confirm Python is installed correctly.
Setting Up a Virtual Environment:
   1. Install virtualenv (Optional but recommended): Open Command Prompt or PowerShell and install virtualenv globally:
   2. Create and Activate Virtual Environment:
      a. Navigate to your project directory in Command Prompt or PowerShell. 
      b. Create a virtual environment by running: Replace venv with your preferred environment name.
      c. Activate the virtual environment with: (The command prompt will now show (venv) indicating the virtual environment is active.)
   3. Install Packages (Optional): 
      a. While the virtual environment is active, install packages using pip:
   4. Deactivate Virtual Environment:
      a. To deactivate the virtual environment and return to the global Python environment, use:


3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

# Print "Hello, World!" to the console
print("Hello, World!")

Explanation:
   1. Comments:
      # Print "Hello, World!" to the console is a comment in Python, starting with #. Comments are ignored during execution and are used for documentation.
   2. Print Statement:
      a. print("Hello, World!") is a built-in function in Python used to display text or other data types on the console.
      b. "Hello, World!" is a string literal enclosed in double quotes. Strings in Python can be enclosed in either single or double quotes.


4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
Basic Data Types in Python
   1. Integer (int): Whole numbers, e.g., 5, -3.
   2. Float (float): Decimal numbers, e.g., 3.14, -0.001.
   3. String (str): Text, enclosed in quotes, e.g., "hello".
   4. Boolean (bool): Truth values, True or False.
   5. List (list): Ordered collection, e.g., [1, 2, 3].
   6. Tuple (tuple): Immutable collection, e.g., (1, 2, 3).
   7. Dictionary (dict): Key-value pairs, e.g., {'name': 'Alice', 'age': 25}.
   8. Set (set): Unique items, e.g., {1, 2, 3}.
Python Script Demonstrating Data Types:
# Integer
age = 25
print("Age:", age)
# Float
pi = 3.14159
print("Pi:", pi)
# String
name = "Alice"
print("Name:", name)
# Boolean
is_student = True
print("Is student:", is_student)
# List
fruits = ["apple", "banana", "cherry"]
print("Fruits:", fruits)
# Tuple
coordinates = (10.0, 20.0)
print("Coordinates:", coordinates)
# Dictionary
person = {"name": "Bob", "age": 30}
print("Person:", person)
# Set
unique_numbers = {1, 2, 3, 2, 1}
print("Unique numbers:", unique_numbers)

Explanation:
   1. Integer (int): age is an integer variable storing the value 25.
   2. Float (float): pi is a float variable storing the value 3.14159.
   3. String (str): name is a string variable storing the value "Alice".
   4. Boolean (bool): is_student is a boolean variable storing the value True.
   5. List (list): fruits is a list variable storing ["apple", "banana", "cherry"].
   6. Tuple (tuple): coordinates is a tuple variable storing (10.0, 20.0).
   7. Dictionary (dict): person is a dictionary variable storing {"name": "Bob", "age": 30}.
   8. Set (set): unique_numbers is a set variable storing {1, 2, 3} (duplicate values are automatically removed).


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

1. Conditional Statements and Loops in Python
      a. Conditional Statements:Conditional statements execute code based on whether a condition is true or false.
         i. if: Runs code if a condition is true.
         ii. elif: Checks another condition if the previous conditions are false.
         iii. else: Runs code if all previous conditions are false.
Example of if-else Statement:
age = 18
if age < 18:
    print("You are a minor.")
elif age == 18:
    print("You just became an adult.")
else:
    print("You are an adult.")
2. Loops:
   Loops allow you to repeat code multiple times.
      a. for Loop: Iterates over a sequence (list, tuple, dictionary, set, or string).
Example of a for loop
   fruits = ["apple", "banana", "cherry"]
   for fruit in fruits:
    print(fruit)


6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

Functions are reusable blocks of code that perform specific tasks, making programs modular, maintainable, and easier to understand.
Benefits of Functions:
   1. Reusability: Write code once, use it multiple times.
   2. Modularity: Break down complex problems into manageable parts.
   3. Maintainability: Easier to debug and update.
   4. Abstraction: Hide complex details, providing a simple interface.
Here's a function that takes two arguments and returns their sum:
   def add_numbers(a, b):
    """Returns the sum of a and b."""
    return a + b
Calling the Function:
   result = add_numbers(3, 5)
   print("The sum is:", result)
Complete Example:
   # Define the function
   def add_numbers(a, b):
    """Returns the sum of a and b."""
    return a + b
   # Call the function
   result = add_numbers(3, 5)
   print("The sum is:", result)


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

Differences Between Lists and Dictionaries in Python
   1. Lists:
      a. Ordered collection of items.
      b. Indexed by positions (starting from 0).
      c. Allows duplicates.
      d. Syntax: list_name = [item1, item2, item3].
   2. Dictionaries:
      a. Unordered collection of key-value pairs.
      b. Indexed by unique keys.
      c. Keys are typically strings, but can be other immutable types.
      d. Syntax: dict_name = {key1: value1, key2: value2}.
Script Demonstrating Lists and Dictionaries:
# Create a list of numbers
numbers = [1, 2, 3, 4, 5]
# Create a dictionary with key-value pairs
person = {
    "name": "Alice",
    "age": 30,
    "city": "New York"
}
# Basic operations on the list
print("Original list:", numbers)
numbers.append(6)  # Add an element
print("After appending 6:", numbers)
numbers.remove(3)  # Remove an element
print("After removing 3:", numbers)
print("First element:", numbers[0])  # Access an element by index
print("Slice of list:", numbers[1:3])  # Slice the list
# Basic operations on the dictionary
print("Original dictionary:", person)
person["age"] = 31  # Modify a value
print("After updating age:", person)
person["country"] = "USA"  # Add a new key-value pair
print("After adding country:", person)
del person["city"]  # Remove a key-value pair
print("After deleting city:", person)
print("Name:", person["name"])  # Access a value by key
print("Keys:", list(person.keys()))  # Get all keys
print("Values:", list(person.values()))  # Get all values
Explanation:
   1. List Operations:
      a. numbers.append(6): Adds 6 to the list.
      b. numbers.remove(3): Removes 3 from the list.
      c. numbers[0]: Accesses the first element.
      d. numbers[1:3]: Gets a slice of the list from index 1 to 2.
   2. Dictionary Operations:
      a. person["age"] = 31: Updates the value of "age" to 31.
      b. person["country"] = "USA": Adds "country": "USA".
      c. del person["city"]: Removes the "city" key-value pair.
      d. person["name"]: Accesses the value associated with "name".
      e. person.keys(): Returns all keys.
      f. person.values(): Returns all values.


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

Exception handling allows you to manage errors gracefully, preventing your program from crashing. Use try, except, and finally blocks to handle potential errors and execute code regardless of whether an error occurs.
   a. try: Code that might cause an exception.
   b. except: Code that runs if an exception occurs.
   c. finally: Code that always runs, typically for cleanup.
Example:
try:
    # Code that might raise an exception
    num1 = 10
    num2 = 0
    result = num1 / num2
    print("Result:", result)
except ZeroDivisionError:
    # Handle the specific exception
    print("Error: Cannot divide by zero.")
finally:
    # Code that runs no matter what
    print("Execution completed.")
Explanation:
   1. try block: Attempts to divide by zero (result = num1 / num2).
   2. except block: Catches the ZeroDivisionError and prints an error message.
   3. finally block: Prints "Execution completed," regardless of whether an error occurred.


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

Modules in Python are files containing code such as functions, classes, and variables that can be imported and reused in other Python scripts.
Packages are directories containing multiple modules, often with an __init__.py file indicating they are Python packages. 
   1. Importing and Using a Module
         You import modules using import and access their contents using dot notation (.).
Example with the math Module:
import math
print("Square root of 16:", math.sqrt(16))  # Outputs: 4.0
print("Value of pi:", math.pi)  # Outputs: 3.141592653589793
print("Sine of 0 degrees:", math.sin(math.radians(0)))  # Outputs: 0.0
Explanation:
   1. import math: Imports the math module.
   2. math.sqrt(16): Computes the square root of 16.
   3. math.pi: Accesses the constant pi from the math module.
   4. math.sin(math.radians(0)): Calculates the sine of 0 degrees after converting degrees to radians.


10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

   1. To read from a file:
      a. Open the File: Use open() with 'r' mode.
      b. Read Content: Use read(), readline(), or readlines().
      c. Close the File: Use close() or a with statement for automatic closing.
Example: Reading from a Fil
file_path = 'sample.txt'
with open(file_path, 'r') as file:
    content = file.read()
    print(content)
   2. To write to a file:
      a. Open the File: Use open() with 'w' mode.
      b. Write Content: Use write() to write data.
      c. Close the File: Use close() or a with statement
Example: Writing to a File
data = ["Apple", "Banana", "Cherry", "Date"]
output_file_path = 'output.txt'
with open(output_file_path, 'w') as file:
    for item in data:
        file.write(item + '\n')


# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


