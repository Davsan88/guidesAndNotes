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






## Working with Lists
### Adding by Index: Insert
### Removing by Index: Pop
### Consecutive Lists: Range
### Length
### Slicing Lists
### Counting in a List
### Sorting Lists I sort()
### Sorting Lists II sorted()
## Tuples
## Combining Lists: The Zip Function