# JavaScript Quick Guide

JavaScript (JS) is a dynamic programming language widely used for web development to create interactive and dynamic web pages. It runs on the client's browser without the need for server-side processing. JavaScript can manipulate HTML content, respond to user events, validate data, and much more, making it an essential tool for front-end web development. It can also be used on the server-side through environments such as Node.js.

## Introduction to JavaScript

### `console.log()`

The `console.log()` method is used to print any specified message or variable value to the browser console. It's a helpful debugging tool.

```javascript
console.log("Hello, world!");
```

## Type of Comments

In JavaScript, comments can be written in two ways:

- Single-line comments, starting with `//`
- Multi-line comments, enclosed between `/*` and */`

Examples:
```javascript
// This is a single-line comment

/*
This is a multi-line comment
which spans over multiple lines
*/
```

## Data Types

JavaScript supports dynamic types; this means you don't have to declare the type of a variable ahead of time. The main data types are:

- **String**: Represents textual data, e.g., `"hello"`.
- **Number**: Represents both integer and floating-point numbers, e.g., `42` or `3.14`.
- **Boolean**: Represents a logical entity having two values: `true` and `false`.
- **Undefined**: Represents a variable that has not been assigned a value.
- **Null**: Represents the intentional absence of any object value.
- **Object**: Collections of properties, e.g., `{name: "Alice", age: 30}`.
- **Symbol**: Represents a unique identifier.

Example:
```javascript
let name = "Alice"; // String
let age = 30; // Number
let isStudent = false; // Boolean
```

## Arithmetic Operators

JavaScript supports several arithmetic operators, including:

- `+` Addition
- `-` Subtraction
- `*` Multiplication
- `/` Division
- `%` Modulus (remainder)
- `++` Increment
- `--` Decrement

Example:
```javascript
let result;

result = 10 + 5; // 15
result = 10 - 5; // 5
result = 10 * 5; // 50
result = 10 / 5; // 2
result = 10 % 3; // 1

let x = 5;
x++; // x is now 6
x--; // x is now 5 again
```

## String Concatenations

In JavaScript, strings can be concatenated using the `+` operator or the `${}` syntax within template literals for more readability and ease, especially when variables are involved.

Examples:
```javascript
let greeting = "Hello, " + "world!";
console.log(greeting); // "Hello, world!"

let name = "Alice";
let personalizedGreeting = `Hello, ${name}!`;
console.log(personalizedGreeting); // "Hello, Alice!"
```

## Properties

Properties are values associated with objects in JavaScript. Every object has properties, and these properties can be both primitive values or functions (in which case, the properties are called methods).

Example:
```javascript
let person = {
    name: "Alice",
    age: 30
};

console.log(person.name); // "Alice"
console.log(person.age); // 30
```

## Methods

Methods are functions that are stored as object properties. JavaScript provides numerous built-in methods to manipulate objects, arrays, strings, etc.

Example:
```javascript
let message = "Hello, world!";
let length = message.length; // 13
console.log(length);

let uppercasedMessage = message.toUpperCase();
console.log(uppercasedMessage); // "HELLO, WORLD!"
```

## Built-in Objects

JavaScript comes with a number of built-in objects that provide functionality necessary for scripting web pages. These objects include, but are not limited to, `Array`, `Date`, `Math`, and `RegExp`.

Examples:
```javascript
// Array
let fruits = ["Apple", "Banana", "Cherry"];
console.log(fruits.length); // 3

// Date
let now = new Date();
console.log(now);

// Math
let pi = Math.PI;
console.log(pi); // 3.141592653589793

// RegExp
let pattern = /hello/;
console.log(pattern.test("hello world!")); // true
```

# Variables

Variables are used to store data values. JavaScript uses `var`, `let`, and `const` for variable declarations, each with its own scope and use case.

## var, let, const

- **var**: Declares a variable, optionally initializing it to a value. `var` is function-scoped.
- **let**: Declares a block-scoped, local variable, optionally initializing it to a value.
- **const**: Declares a block-scoped, read-only named constant.

Example:
```javascript
var oldWay = "I'm old school";
let newWay = "I prefer block scope";
const unchangeable = "You can't change me";
```

## Mathematical Assignment Operators

JavaScript provides operators that perform mathematical operations and assign the result to a variable, such as `+=`, `-=`, `*=`, `/=`, and `%=`.

Example:
```javascript
let x = 10;
x += 5; // x is now 15
x -= 3; // x is now 12
x *= 2; // x is now 24
x /= 4; // x is now 6
x %= 5; // x is now 1
```

## Increment and Decrement Operator

The `++` and `--` operators increment and decrement a variable's value by one, respectively.

Example:
```javascript
let counter = 0;
counter++; // counter is now 1
counter--; // counter is back to 0
```

## String Concatenation with Variables

Strings can be concatenated using the `+` operator along with variables.

Example:
```javascript
let greeting = "Hello";
let name = "Alice";
console.log(greeting + ", " + name + "!"); // "Hello, Alice!"
```

## String Interpolation

String interpolation is a method of inserting values into a string. It is accomplished with template literals.

### Template Literals

Template literals are string literals allowing embedded expressions, denoted by the backtick (`) characters.

Example:
```javascript
let name = "Alice";
console.log(`Hello, ${name}!`); // "Hello, Alice!"
```

## typeof operator

The `typeof` operator is used to determine the type of a JavaScript variable.

Example:
```javascript
console.log(typeof "Hello, world!"); // "string"
console.log(typeof 42); // "number"
console.log(typeof true); // "boolean"
```

# Conditional Statements

Conditional statements are used to perform different actions based on different conditions. In JavaScript, we have several types of conditional statements.

## if, else if, and else statements

The `if` statement executes a block of code if a specified condition is true. If the condition is false, another block of code can be executed using `else`. The `else if` statement can specify a new condition if the first condition is false.

Example:
```javascript
if (condition1) {
   // block of code to be executed if condition1 is true
} else if (condition2) {
   // block of code to be executed if the condition1 is false and condition2 is true
} else {
   // block of code to be executed if the condition1 is false and condition2 is false
}
```
## Comparison Operators

Comparison operators are used in logical statements to determine equality or difference between variables or values.

- `==` equal to
- `===` strictly equal (value and type)
- `!=` not equal
- `!==` strictly not equal
- `>` greater than
- `<` less than
- `>=` greater than or equal to
- `<=` less than or equal to

Example:
```javascript
if (age >= 18) {
    console.log("You are an adult.");
}
```

## Logical Operators

Logical operators are used to determine the logic between variables or values.

- `&&` logical and
- `||` logical or
- `!` logical not

Example:
```javascript
if (age > 18 && nationality === 'Canadian') {
    console.log("You are a Canadian adult.");
}
```

### Short Circuit Evaluation

Conditionally executing code without the need for `if` statements.

- **`||` (Logical OR)**: In an expression of the form `A || B`, JavaScript evaluates `A`. If `A` can be converted to `true`, it returns `A`; otherwise, it returns `B`. This means if `A` is truthy, `B` is not even evaluated.

Example:
```javascript
let result = someValue || 'default value';
```
In this example, `result` will be assigned `someValue` if `someValue` is truthy; otherwise, it will be assigned `'default value'`.

- **`&&` (Logical AND)**: In an expression of the form `A && B`, JavaScript evaluates `A`. If `A` can be converted to `false`, it returns `A`; otherwise, it returns `B`. This means if `A` is falsy, `B` is not even evaluated.

Example:
```javascript
let result = value1 && value2;
```



