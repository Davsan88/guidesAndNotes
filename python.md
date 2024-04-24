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


## User Input
# Control Flow
## Boolean Expressions
## Relational Operators: Equals and Not Equals
## Boolean Variables
## If Statement
## Relational Operators II 
    > greater than
    >= greater than or equal to
    < less than
    <= less than or equal to
## Boolean Operators: and
## Boolean Operators: or
## Boolean Operators: not