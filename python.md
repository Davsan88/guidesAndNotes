# Hello World: Welcome to Python

Welcome to Python, a powerful and versatile programming language that's widely used for web development, data analysis, artificial intelligence, scientific computing, and more.

## Comments

Comments in Python are created using the `#` symbol. Anything following the `#` on the same line is ignored by the Python interpreter.

- Example:
  ```python
  # This is a comment in Python
  ```

## Print

The `print()` function is used to output data to the standard output device (screen).

- Example:
  ```python
  print("Hello, world!")
  ```

## Strings

Strings in Python are sequences of characters enclosed in quotes. You can use either single quotes (`'`) or double quotes (`"`).

- Example:
  ```python
  print("This is a string.")
  print('This is also a string.')
  ```

 ## Variables

Variables are used to store data values. In Python, a variable is created the moment you first assign a value to it.

- Example:
  ```python
  x = 5
  y = "Hello, Python!"
  print(x)
  print(y)
  ```

## Errors

Two common errors that we encounter while writing Python are SyntaxError and NameError.

SyntaxError means there is something wrong with the way your program is written.

NameError occurs when the Python interpreter sees a word it does not recognize.

- Example:
  ```python
  # This will raise an error because "test" is not defined
  print(test)
  ```

## Numbers

Python supports various types of numbers, such as integers and floating-point numbers.

- Example:
  ```python
  x = 10    # Integer
  y = 10.5  # Floating-point number
  print(x, y)
  ```

## Calculations

Python can be used as a calculator to perform arithmetic.

- Example:
  ```python
  print(1 + 1)  # Addition
  print(2 * 3)  # Multiplication
  print(5 - 3)  # Subtraction
  print(8 / 2)  # Division
  ```

## Changing Numbers

Variables that are assigned numeric values can be treated the same as the numbers themselves.

- Example:
  ```python
    coffee_price = 1.50
    number_of_coffees = 4

    # Prints "6.0"
    print(coffee_price * number_of_coffees)

    # Updating the price 
    coffee_price = 2.00
    # Prints "8.0"
    print(coffee_price * number_of_coffees)
  ```

## Exponents

Python supports exponents as well, which allows for power calculations.

- Example:
  ```python
  # 2 raised to the power of 3
  print(2 ** 3)
  ```

## Modulo

The modulo operator (`%`) in Python returns the remainder of a division operation between two numbers.

- Example:
  ```python
  print(10 % 3)  # Outputs: 1 because 10 divided by 3 leaves a remainder of 1
  ```

## Concatenation

In Python, you can concatenate strings using the `+` operator, which combines them into one string.

- Example:
  ```python
  greeting = "Hello"
  name = "Alice"
  message = greeting + " " + name + "!"
  print(message)  # Outputs: Hello Alice!
  ```

## Plus Equals

The `+=` operator in Python is used to add the right operand to the left operand and assign the result to the left operand. It's commonly used to shorten the syntax for incrementing the value of a variable.

- Example:
  ```python
  count = 0
  count += 1  # Equivalent to count = count + 1
  print(count)  # Outputs: 1
  ```

## Multi-line Strings

Multi-line strings in Python can be created using triple quotes (`'''` or `"""`). This is useful for strings that span multiple lines.

- Example:
  ```python
  multi_line_string = """
  This is a string that
  spans multiple lines
  in Python.
  """
  print(multi_line_string)
  ```

## User Input

In Python, user input can be obtained using the `input()` function. This function pauses the program and waits for the user to enter some input from the keyboard.

- Example:
  ```python
  user_name = input("Enter your name: ")
  print(f"Hello, {user_name}!")
  ```


>This guide provides a brief overview of basic concepts in Python to get you started with writing simple programs. Python's simplicity and readability make it an excellent choice for beginners and experts alike.


# Control Flow

Control flow in Python refers to the sequence in which code statements are executed. It can be managed using various control structures such as conditional statements and loops.

## Boolean Expressions

A Boolean expression is an expression that evaluates to produce a result which is either `True` or `False`.

- Example:
  ```python
  print(10 > 9)  # Outputs: True
  print(10 == 9) # Outputs: False
  ```

## Relational Operators: Equals and Not Equals

Relational operators compare the values on either side of them and decide the relation among them. `==` is the equals operator, and `!=` is the not equals operator.

- Example:
  ```python
  print(5 == 5)   # Outputs: True
  print(5 != 5)   # Outputs: False
  ```

## Boolean Variables

Boolean variables are variables that are either set to `True` or `False`.

- Example:
  ```python
  is_logged_in = True
  if is_logged_in:
      print("User is logged in.")
  ```

## If Statement

The `if` statement is used to test a specific condition. If the condition is true, a block of code will be executed.

- Example:
  ```python
  age = 20
  if age >= 18:
      print("You are old enough to vote.")
  ```

## Relational Operators II

Relational operators are used to compare two values. Here are more examples:

- `>` (greater than)
- `>=` (greater than or equal to)
- `<` (less than)
- `<=` (less than or equal to)

- Example:
  ```python
  print(10 > 5)   # Outputs: True
  print(10 >= 10) # Outputs: True
  print(5 < 10)   # Outputs: True
  print(5 <= 4)   # Outputs: False
  ```

## Boolean Operators: and

The `and` operator returns `True` if both the operands (left side and right side) are true.

- Example:
  ```python
  print(True and True)   # Outputs: True
  print(True and False)  # Outputs: False
  ```

  ## Boolean Operators: or

The `or` operator returns `True` if at least one of the operands is true.

- Example:
  ```python
  print(True or False)  # Outputs: True
  print(False or False) # Outputs: False
  ```

  ## Boolean Operators: not

The `not` operator returns `True` if the operand is false.

- Example:
  ```python
  print(not False)  # Outputs: True
  print(not True)   # Outputs: False
  ```

## Else Statements

The `else` statement follows an `if` statement, and its block of code runs if the `if` statement condition is false.

- Example:
  ```python
  age = 16
  if age >= 18:
      print("You are old enough to vote.")
  else:
      print("You are not old enough to vote.")
  ```

  ## Else If Statements

The `elif` (short for else if) statement allows you to check multiple expressions for `True` and execute a block of code as soon as one of the conditions evaluates to `True`.

- Example:
  ```python
  age = 20
  if age < 13:
      print("You are a child.")
  elif age < 20:
      print("You are a teenager.")
  else:
      print("You are an adult.")
  ```

>These operators and control statements form the basis of decision-making in Python, allowing for more complex and dynamic behavior in programs.


# Errors in Python

Python can encounter various types of errors, and understanding them is key to effective debugging. Here are some common errors:

## Syntax Errors

Syntax errors occur when Python can't understand what you've written due to incorrect syntax. These are the most common kind of errors you encounter while learning Python.

- Example:
  ```python
  print("Hello world"
  # Missing closing parenthesis, will cause a syntax error
  ```

## Name Errors

A NameError is thrown when Python tries to evaluate a variable that has not been assigned yet.

- Example:
  ```python
  print(age)
  # If 'age' is not defined before this line, this will raise a NameError.
  ```

## Type Errors

Type errors occur when an operation or function is applied to an object of inappropriate type.

- Example:
  ```python
  '5' + 5
  # Trying to add a string to an integer, which will raise a TypeError.
  ```

>Understanding these errors will help you debug your Python code more efficiently, preventing common mistakes and improving your coding skills.

# Lists

Lists in Python are ordered collections that are changeable and can contain items of different types.

## List Methods

Python provides several methods that you can use to manipulate lists, such as `append()`, `extend()`, `pop()`, `remove()`, and more.

- Example:
  ```python
  fruits = ['apple', 'banana', 'cherry']
  fruits.append('orange')  # Adds 'orange' to the end
  print(fruits)  # Outputs: ['apple', 'banana', 'cherry', 'orange']
  ```

## Growing a List: Append

The `append()` method adds a single item to the end of the list.

- Example:
  ```python
  fruits = ['apple', 'banana', 'cherry']
  fruits.append('orange')
  print(fruits)  # Outputs: ['apple', 'banana', 'cherry', 'orange']
  ```

## Growing a List: Plus (+)

You can concatenate two lists using the `+` operator to create a new list.

- Example:
  ```python
  fruits = ['apple', 'banana', 'cherry']
  other_fruits = ['mango', 'pineapple']
  all_fruits = fruits + other_fruits
  print(all_fruits)  # Outputs: ['apple', 'banana', 'cherry', 'mango', 'pineapple']
  ```

## Accessing List Elements

List elements can be accessed by their index, starting from 0 for the first element.

- Example:
  ```python
  print(fruits[0])  # Outputs: 'apple'
  ```

## Accessing List Elements: Negative Index

Negative indices can be used to access elements from the end of the list, starting with -1 for the last element.

- Example:
  ```python
  print(fruits[-1])  # Outputs: 'cherry' (the last element)
  print(fruits[-2])  # Outputs: 'banana' (second to last element)
  ```

## Modifying List Elements

You can modify an element in a list by accessing it through its index and assigning a new value.

- Example:
  ```python
  fruits = ['apple', 'banana', 'cherry']
  fruits[1] = 'mango'  # Change 'banana' to 'mango'
  print(fruits)  # Outputs: ['apple', 'mango', 'cherry']
  ```

  ## Shrinking a List: Remove

The `remove()` method removes the first occurrence of a specified value from a list.

- Example:
  ```python
  fruits.remove('mango')  # Removes 'mango' from the list
  print(fruits)  # Outputs: ['apple', 'cherry']
  ```

  ## Two-Dimensional (2D) Lists

A two-dimensional (2D) list is essentially a list of lists and can be used to store tables or matrix-like structures.

### Accessing 2D Lists

Elements in a 2D list are accessed using two indices: the first specifies the row, and the second specifies the column.

- Example:
  ```python
  matrix = [
      [1, 2, 3],
      [4, 5, 6],
      [7, 8, 9]
  ]
  print(matrix[0][1])  # Outputs: 2 (First row, second column)
  ```

  ### Modifying 2D Lists

You can modify an element in a 2D list by accessing its row and column indices and assigning a new value.

- Example:
  ```python
  matrix[1][1] = 99  # Changes the value of the second row and second column to 99
  print(matrix)  # Outputs: [[1, 2, 3], [4, 99, 6], [7, 8, 9]]
  ```

### Shrinking a 2D List: Remove

You can remove an entire row from a 2D list using the `remove()` method or delete an item from a specific row.

- Example:
  ```python
  matrix.remove([4, 99, 6])  # Removes the entire row
  print(matrix)  # Outputs: [[1, 2, 3], [7, 8, 9]]

  del matrix[0][1]  # Deletes the second item of the first row
  print(matrix)  # Outputs: [[1, 3], [7, 8, 9]]
  ```

>Manipulating 2D lists is fundamental in applications where data is structured in a tabular form, such as in spreadsheets or databases.

# Working with Lists

Working with lists in Python involves manipulating them through various methods and functions, allowing for dynamic and flexible data management.

## Adding by Index: Insert

The `insert()` method inserts an element at a specified position in the list.

- Example:
  ```python
  fruits = ['apple', 'mango', 'cherry']
  fruits.insert(1, 'banana')  # Inserts 'banana' at index 1
  print(fruits)  # Outputs: ['apple', 'banana', 'mango', 'cherry']
  ```

## Removing by Index: Pop

The `pop()` method removes the element at the specified position in the list and returns it. If no index is specified, `pop()` removes and returns the last item in the list.

- Example:
  ```python
  last_fruit = fruits.pop()  # Removes the last item
  print(last_fruit)  # Outputs: 'cherry'
  print(fruits)  # Outputs: ['apple', 'banana', 'mango']
  ```

## Consecutive Lists: Range

The `range()` function generates a sequence of numbers, which is often used to iterate over with for loops to perform actions a certain number of times.

- Example:
  ```python
  numbers = list(range(1, 6))  # Creates a list of numbers from 1 to 5
  print(numbers)  # Outputs: [1, 2, 3, 4, 5]
  ```

## Length

The `len()` function returns the number of items in a list.

- Example:
  ```python
  print(len(fruits))  # Outputs: 3
  ```

## Slicing Lists

Slicing in Python allows you to create a new list from a subset of an existing list.

- Example:
  ```python
  print(fruits[1:3])  # Outputs: ['banana', 'mango']
  ```

## Counting in a List

The `count()` method returns the number of times a specified value appears in the list.

- Example:
  ```python
  print(fruits.count('banana'))  # Outputs: 1
  ```

  ## Sorting Lists I: sort()

The `sort()` method sorts the list in place.

- Example:
  ```python
  fruits.sort()
  print(fruits)  # Outputs: ['apple', 'banana', 'mango']
  ```

## Sorting Lists II: sorted()

The `sorted()` function returns a new list containing all items from the original list in ascending order.

- Example:
  ```python
  sorted_fruits = sorted(fruits, reverse=True)  # Sorts the list in descending order
  print(sorted_fruits)  # Outputs: ['mango', 'banana', 'apple']
  ```

## Tuples

Tuples are immutable sequences, typically used to store collections of heterogeneous data.

- Example:
  ```python
  tuple_example = (1, 'hello', 3.14)
  print(tuple_example)  # Outputs: (1, 'hello', 3.14)
  ```

## Combining Lists: The Zip Function

The `zip()` function is used to combine several lists into a tuple of pairs.

- Example:
  ```python
  names = ['Alice', 'Bob', 'Charlie']
  ages = [25, 30, 35]
  combined = list(zip(names, ages))
  print(combined)  # Outputs: [('Alice', 25), ('Bob', 30), ('Charlie', 35)]
  ```

>These methods and functions provide comprehensive ways to manipulate and utilize lists in Python, crucial for effective data handling and operations.


# Loops

Loops in Python are a fundamental concept used to repeat a block of code multiple times.

## For Loops: Introduction

For loops are used for iterating over a sequence (such as a list, tuple, dictionary, set, or string).

- Example:
  ```python
  for item in ['apple', 'banana', 'cherry']:
      print(item)
  ```

## For Loops: Using Range

The `range()` function is commonly used with for loops to specify the number of iterations.

- Example:
  ```python
  for i in range(5):  # Iterates over a sequence of numbers from 0 to 4
      print(i)
  ```

## While Loops: Introduction

While loops repeat as long as a certain boolean condition is met.

- Example:
  ```python
  count = 0
  while count < 5:
      print(count)
      count += 1
  ```

## While Loops: Lists

While loops can be used to iterate through lists when the length of the list is unknown or to apply complex conditional logic.

- Example:
  ```python
  fruits = ['apple', 'banana', 'cherry']
  while fruits:
      print(fruits.pop())
  ```

## Infinite Loops

An infinite loop occurs when the condition of the loop can never become false. These are generally used deliberately, such as in server processes that run continuously.

- Example:
  ```python
  while True:
      print("This is an infinite loop")
  ```

## Loop Control: Break

The `break` statement is used to exit a loop when a certain condition is met.

- Example:
  ```python
  for num in range(10):
      if num == 5:
          break  # Breaks out of the loop when num is 5
      print(num)
  ```

## Loop Control: Continue

The `continue` statement skips the current iteration of the loop and moves to the next iteration.

- Example:
  ```python
  for num in range(10):
      if num % 2 == 0:
          continue  # Skips the print statement for even numbers
      print(num)
  ```

## Nested Loops

A nested loop is a loop inside a loop.

- Example:
  ```python
  for i in range(3):
      for j in range(3):
          print(i, j)
  ```

## List Comprehensions: Introduction

List comprehensions provide a concise way to create lists. It involves brackets containing an expression followed by a `for` clause.

- Example:
  ```python
  squares = [x**2 for x in range(10)]
  print(squares)
  ```

## List Comprehensions: Conditionals

List comprehensions can also contain conditionals.

- Example:
  ```python
  even_squares = [x**2 for x in range(10) if x % 2 == 0]
  print(even_squares)
  
  no_if   = [x * 2 for x in numbers]
  if_only = [x * 2 for x in numbers if x < 0]
  if_else = [x * 2 if num < 0 else x * 3 for x in numbers]
  ```

>Loops and list comprehensions are powerful tools in Python, allowing for efficient and readable data processing and manipulation.


# Functions

Functions in Python are blocks of code that execute a specific task and can be reused throughout your programs.

## Defining a Function

Functions are defined using the `def` keyword followed by a name, parentheses, and a colon. The indented block of code following the colon is executed when the function is called.

- Example:
  ```python
  def greet():
      print("Hello, World!")
  ```

## Calling a Function

A function is called by writing the function's name followed by parentheses.

- Example:
  ```python
  greet()  # Outputs: Hello, World!
  ```

## Whitespace & Execution Flow

In Python, whitespace is used to define the scope of loops, functions, and classes. The code block within a function must be indented.

- Example:
  ```python
  def function():
      print("Inside function")  # Correct indentation
  # print("Outside function")  # This line is not part of the function due to incorrect indentation
  ```

## Parameters & Arguments

Parameters are specified in the function definition and represent the data that can be input into a function. Arguments are the actual values passed to the function.

### Multiple Parameters

Functions can accept more than one parameter.

- Example:
  ```python
  def add(a, b):
      print(a + b)
  add(5, 3)  # Outputs: 8
  ```

### Types of Arguments

- **Positional Arguments:** Arguments that need to be included in the proper position or order.
- **Keyword Arguments:** Arguments identified by the parameter name.
- **Default Arguments:** Arguments that assume a default value if a value is not provided in the function call.

- Example:
  ```python
  def display_info(name, age=30):
      print(f"Name: {name}, Age: {age}")
  display_info("Alice", age=25)  # Outputs: Name: Alice, Age: 25
  display_info("Bob")            # Outputs: Name: Bob, Age: 30
  ```

## [Built-in Functions vs User Defined Functions](https://docs.python.org/3/library/functions.html)

Python provides many built-in functions like `print()`, `len()`, and `range()`, which are documented in the Python Standard Library. Users can also define their own functions to perform custom tasks.

## Variable Access

Variables defined inside a function are local to that function, while variables defined outside are global and can be accessed by any function within the same program.

- Example:
  ```python
  x = "global"
  
  def access_variable():
      print(x)
  
  access_variable()  # Outputs: global
  ```

## Returns

Functions can return values using the `return` statement.

### Multiple Returns

A function can return multiple values separated by commas, which Python will automatically package into a tuple.

- Example:
  ```python
  def get_data():
      name = "Alice"
      age = 25
      return name, age  # Returns a tuple ('Alice', 25)
  
  result = get_data()
  print(result)  # Outputs: ('Alice', 25)
  ```

>Functions are a crucial part of Python programming, helping to keep your code organized, reusable, and maintainable.


# Strings

Strings in Python are sequences of characters used for storing and manipulating text.

## Strings are Lists

Technically, strings are not lists, but they can be treated similarly because they are sequences. You can access individual characters using indexing.

- Example:
  ```python
  my_string = "Hello"
  print(my_string[0])  # Outputs: 'H'
  ```

## Slicing a String

Slicing is used to get a substring of the string. It is done by specifying the start index and the end index, separated by a colon, within square brackets.

- Example:
  ```python
  print(my_string[1:4])  # Outputs: 'ell'
  ```

### Slicing using len()

You can use the `len()` function with slicing to extract characters from the string up to its length.

- Example:
  ```python
  print(my_string[:len(my_string)])  # Outputs: 'Hello'
  ```

## Concatenating Strings

Strings can be concatenated using the `+` operator to combine them into one string.

- Example:
  ```python
  first_name = "John"
  last_name = "Doe"
  full_name = first_name + " " + last_name
  print(full_name)  # Outputs: 'John Doe'
  ```

## Negative Indices

Negative indices can be used to access characters from the end of the string.

- Example:
  ```python
  print(my_string[-1])  # Outputs: 'o', the last character of "Hello"
  ```

## Strings are Immutable

Once a string is created, the elements within it cannot be changed.

- Example:
  ```python
  # my_string[0] = 'Y'  # This would raise a TypeError
  ```

## Escape Characters

Escape characters let you include special characters in strings.

- Example:
  ```python
  print("He said, \"Hello, World!\"")  # Outputs: He said, "Hello, World!"
  ```

## Iterating through Strings

Strings can be iterated over with a loop to access each character.

### Using counter variables

- Example:
  ```python
  for i in range(len(my_string)):
      print(my_string[i])
  ```

## Strings and Conditionals

You can use conditionals to check for the presence of a specific character or substring within a string.

- Example:
  ```python
  if "e" in my_string:
      print("'e' is in the string.")
  ```

>Strings are a fundamental type in Python that are used in almost every aspect of the language, from data manipulation to outputs. Knowing how to work with strings effectively is crucial for any Python programmer.


# String Methods

String methods in Python are built-in functionalities that you can call on string objects to perform common tasks.

## Formatting Methods

- `.lower()`: Converts all characters in the string to lowercase.
- `.upper()`: Converts all characters in the string to uppercase.
- `.title()`: Converts the first character of each word to uppercase and the rest to lowercase.

- Example:
  ```python
  greeting = "Hello, World!"
  print(greeting.lower())  # Outputs: 'hello, world!'
  print(greeting.upper())  # Outputs: 'HELLO, WORLD!'
  print(greeting.title())  # Outputs: 'Hello, World!'
  ```

  ## Splitting Strings

The `.split()` method divides a string into a list where each word is a list item.

- Example:
  ```python
  sentence = "Hello, world, welcome to Python."
  words = sentence.split(", ")
  print(words)  # Outputs: ['Hello', 'world', 'welcome to Python.']
  ```

### Splitting Strings with Escape Sequences

You can use escape sequences like `\n` (new line) or `\t` (tab) as separators.

- Example:
  ```python
  data = "Hello\nWorld\nPython"
  lines = data.split("\n")
  print(lines)  # Outputs: ['Hello', 'World', 'Python']
  ```

  ## Joining Strings

The `.join()` method combines a list of strings into a single string with a specified separator.

- Example:
  ```python
  words = ['Earth', 'Mars', 'Venus']
  sentence = ", ".join(words)
  print(sentence)  # Outputs: 'Earth, Mars, Venus'
  ```

## Joining Strings

The `.join()` method combines a list of strings into a single string with a specified separator.

- Example:
  ```python
  words = ['Earth', 'Mars', 'Venus']
  sentence = ", ".join(words)
  print(sentence)  # Outputs: 'Earth, Mars, Venus'
  ```

## .replace()

`.replace()` replaces a specified phrase with another specified phrase.

- Example:
  ```python
  text = "Hello, Mars!"
  text = text.replace("Mars", "World")
  print(text)  # Outputs: 'Hello, World!'
  ```

  ## .find()

`.find()` searches the string for a specified value and returns the position of where it was found or `-1` if it's not found.

- Example:
  ```python
  position = greeting.find("World")
  print(position)  # Outputs: 7
  ```

## .find()

`.find()` searches the string for a specified value and returns the position of where it was found or `-1` if it's not found.

- Example:
  ```python
  position = greeting.find("World")
  print(position)  # Outputs: 7
  ```

>These string methods enhance the functionality of handling and manipulating strings in Python, making string operations more efficient and streamlined.


# Modules

Modules in Python are files containing Python code. They can include functions, classes, and variables that you can use in your programs.

## Modules Python Datetime

The `datetime` module provides classes for manipulating dates and times.

- Example:
  ```python
  import datetime
  now = datetime.datetime.now()
  print(now)  # Outputs the current date and time, e.g., 2023-04-12 14:23:05.678937
  ```

## Modules Python Random

The `random` module is used to perform random generations, from picking a random element from a range or list to generating random numbers.

- Example:
  ```python
  import random
  print(random.randint(1, 100))  # Outputs a random integer between 1 and 100
  ```

## Modules Python Namespaces

Namespaces in Python are mappings from names to objects. They help avoid naming conflicts by isolating identifiers within modules.

- Example:
  ```python
  # Suppose we have two modules, module1 and module2, each with a function named 'greet'
  import module1
  import module2

  module1.greet()  # Calls the 'greet' function from module1
  module2.greet()  # Calls the 'greet' function from module2
  ```

## Modules Python Decimals

The `decimal` module provides support for fast correctly-rounded decimal floating point arithmetic.

- Example:
  ```python
  from decimal import Decimal
  result = Decimal('0.1') + Decimal('0.2')
  print(result)  # Outputs: 0.3, correctly handling floating-point arithmetic that can be problematic with floats
  ```

## Modules Python Files and Scope

Modules also define their own scope, meaning that variables defined in a module are generally only accessible within that module unless explicitly exported.

- Example:
  ```python
  # In a module file called 'mymodule.py', define:
  my_var = "visible in module"

  # In another Python script:
  import mymodule
  print(mymodule.my_var)  # Access the variable 'my_var' from 'mymodule'
  ```

>Python's modularity is one of its most significant features, allowing developers to organize their code neatly and reuse code effectively.


# Dictionaries: Creating Dictionaries

Dictionaries in Python are data structures used to store data values in key:value pairs.

## Introduction to Python Dictionaries

A dictionary is a collection which is unordered, changeable, and indexed. In Python, dictionaries are written with curly brackets, and they have keys and values.

## Make a Dictionary

You can create a dictionary by placing a sequence of elements within curly braces `{}` separated by commas. Each element is a pair expressed as `key: value`.

- Example:
  ```python
  person = {"name": "John", "age": 30, "city": "New York"}
  print(person)  # Outputs: {'name': 'John', 'age': 30, 'city': 'New York'}
  ```

## Invalid Keys

Keys in dictionaries must be of a type that is immutable. This means you can use strings, numbers, and tuples as dictionary keys but not lists, dictionaries, or other mutable types.

- Example:
  ```python
  # This will cause an error because lists are mutable and cannot be keys
  # my_dict = {[1,2,3]: "Numbers"}
  ```

## Empty Dictionary

You can create an empty dictionary to which you can add keys and values later.

- Example:
  ```python
  empty_dict = {}
  print(empty_dict)  # Outputs: {}
  ```

## Add A Key

Adding or updating a key-value pair is straightforward by using the key index.

- Example:
  ```python
  person['email'] = 'john@example.com'
  print(person)  # Outputs: {'name': 'John', 'age': 30, 'city': 'New York', 'email': 'john@example.com'}
  ```

## Add Multiple Keys

You can add multiple keys and values using the `.update()` method.

- Example:
  ```python
  person.update({"height": 175, "weight": 70})
  print(person)  # Outputs: {'name': 'John', 'age': 30, 'city': 'New York', 'email': 'john@example.com', 'height': 175, 'weight': 70}
  ```

## Overwrite Values

If the key already exists, setting a new value will overwrite the existing value associated with that key.

- Example:
  ```python
  person['name'] = 'Jane'
  print(person)  # Outputs: {'name': 'Jane', 'age': 30, 'city': 'New York', 'email': 'john@example.com', 'height': 175, 'weight': 70}
  ```

## Dict Comprehensions

Dictionary comprehensions offer a concise way to create dictionaries.

- Example:
  ```python
  squares = {x: x*x for x in range(6)}
  print(squares)  # Outputs: {0: 0, 1: 1, 2: 4, 3: 9, 4: 16, 5: 25}
  ```

### Using `zip()`

You can use `zip()` to create dictionaries from two lists that you want to pair up as keys and values.

- Example:
  ```python
  keys = ['name', 'age', 'city']
  values = ['Alice', 28, 'London']
  dictionary = dict(zip(keys, values))
  print(dictionary)  # Outputs: {'name': 'Alice', 'age': 28, 'city': 'London'}
  ```

>Dictionaries are a versatile way to store and manage data in Python, allowing for efficient lookups, insertion, and removal of data entries.


# Dictionaries: Using Dictionaries

Dictionaries in Python provide a flexible way to access, modify, and remove key-value pairs.

## Get a Key

To retrieve the value for a specific key in a dictionary, you simply use the square brackets `[]` with the key.

- Example:
  ```python
  person = {"name": "John", "age": 30}
  print(person["name"])  # Outputs: 'John'
  ```

## Get a Key

To retrieve the value for a specific key in a dictionary, you simply use the square brackets `[]` with the key.

- Example:
  ```python
  person = {"name": "John", "age": 30}
  print(person["name"])  # Outputs: 'John'
  ```

## Get an Invalid Key

Attempting to access a key that does not exist in the dictionary will raise a `KeyError`.

- Example:
  ```python
  # print(person["address"])  # This would raise a KeyError because 'address' is not a key in the dictionary
  ```

## Safely Get a Key

The `.get()` method allows you to retrieve a value for a given key without the risk of a `KeyError`. It returns `None` if the key is not found, unless a default value is provided.

- Example:
  ```python
  address = person.get("address", "No address provided")
  print(address)  # Outputs: 'No address provided'
  ```

## Delete a Key

To delete a key and its corresponding value from a dictionary, you can use the `del` statement or the `.pop()` method.

- Example:
  ```python
  del person["age"]
  # or
  # age = person.pop("age")
  print(person)  # Outputs: {'name': 'John'}
  ```

## Get All Keys

To get a list of all the keys in a dictionary, you can use the `.keys()` method.

- Example:
  ```python
  keys = list(person.keys())
  print(keys)  # Outputs: ['name']
  ```

## Get All Values

The `.values()` method returns a list of all the values in the dictionary.

- Example:
  ```python
  values = list(person.values())
  print(values)  # Outputs: ['John']
  ```

## Get All Items

The `.items()` method returns a list of tuples, each containing a key-value pair.

- Example:
  ```python
  items = list(person.items())
  print(items)  # Outputs: [('name', 'John')]
  ```

>Using these methods and techniques to manipulate dictionaries enhances data handling capabilities in Python, making it easier to implement more complex data structures and algorithms efficiently.


# Files

Handling files in Python allows for data persistence and manipulation of different file formats.

## Reading a File

To read the entire contents of a file, you can use the `open()` function with the `'r'` mode, which stands for "read".

- Example:
  ```python
  with open('example.txt', 'r') as file:
      content = file.read()
      print(content)
  ```

## Iterating Through Lines

You can iterate through each line of a file using a for loop, which is useful for processing each line separately.

- Example:
  ```python
  with open('example.txt', 'r') as file:
      for line in file:
          print(line.strip())
  ```

## Reading a Line

To read a single line from a file, use the `.readline()` method.

- Example:
  ```python
  with open('example.txt', 'r') as file:
      first_line = file.readline()
      print(first_line.strip())
  ```

## Writing a File

To write to a file, open it in `'w'` mode (write). This will overwrite any existing content in the file.

- Example:
  ```python
  with open('newfile.txt', 'w') as file:
      file.write("Hello, World!\n")
  ```

## Appending to a File

To append text to an existing file, open it in `'a'` mode (append).

- Example:
  ```python
  with open('example.txt', 'a') as file:
      file.write("Another line\n")
  ```

## What's With "with"?

The `with` statement automatically manages file opening and closing. It ensures that the file is properly closed after its suite finishes, even if an exception is raised on the way.

- `.close()`: It is important to close a file; failing to do so can lead to corrupted or incomplete files. Using `with` automatically handles this.

## What Is a CSV File?

A CSV (Comma-Separated Values) file stores tabular data in plain text, with each line corresponding to a data record. Each record consists of fields, delimited by commas.

## Reading a CSV File

To read from a CSV file, you can use Python's `csv` module, which allows you to iterate over rows of the CSV.

- Example:
  ```python
  import csv
  with open('example.csv', 'r') as file:
      reader = csv.reader(file)
      for row in reader:
          print(row)
  ```

## Reading Different Types of CSV Files

Sometimes CSV files use different delimiters like semicolons. You can specify the delimiter in the `csv.reader()` method.

- Example:
  ```python
  with open('semicolon.csv', 'r') as file:
      reader = csv.reader(file, delimiter=';')
      for row in reader:
          print(row)
  ```

## Writing a CSV File

You can write to a CSV file using `csv.writer()`. 

- Example:
  ```python
  with open('output.csv', 'w', newline='') as file:
      writer = csv.writer(file)
      writer.writerow(['Name', 'Age'])
      writer.writerow(['Alice', 24])
  ```

## Reading a JSON File

JSON files can be easily managed in Python using the `json` module. To read a JSON file, use the `.load()` method.

- Example:
  ```python
  import json
  with open('data.json', 'r') as file:
      data = json.load(file)
      print(data)
  ```
  
## Reading a JSON File

JSON files can be easily managed in Python using the `json` module. To read a JSON file, use the `.load()` method.

- Example:
  ```python
  import json
  with open('data.json', 'r') as file:
      data = json.load(file)
      print(data)
  ```

## Writing a JSON File

To write to a JSON file, use the `.dump()` method of the `json` module.

- Example:
  ```python
  with open('data.json', 'w') as file:
      json.dump({"Name": "John", "Age": 30}, file)
  ```

## Writing a JSON File

To write to a JSON file, use the `.dump()` method of the `json` module.

- Example:
  ```python
  with open('data.json', 'w') as file:
      json.dump({"Name": "John", "Age": 30}, file)
  ```

>Handling files in Python is crucial for a wide array of tasks, from data analysis to automation.




# Classes
## Types
  type()
## Class
## Instantiation 
## Object-Oriented Programming
## Class Variables
## Methods
## Methods with Arguments
## Constructors
## Instance Variables
## Attribute Functions
  hasattr() & getattr()
## Self

## Everything is an Object
  dir()
## String Representation
  __repr__

