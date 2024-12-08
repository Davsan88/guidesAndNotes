# A Beginner's Guide to Functional Programming

Functional Programming (FP) is a programming paradigm that treats computation as the evaluation of mathematical functions. It emphasizes immutability, pure functions, and avoiding side effects. This guide will introduce you to the core concepts of FP, making it easy for you to understand and start applying them in your coding journey.


## Key Concepts of Functional Programming


### 1. Pure Functions

A pure function always produces the same output given the same input and has no observable side effects.

```javascript
function add(a, b) {
    return a + b;
}
```

- The `add` function is pure because it does not depend on or modify external state.

---


### 2. Immutability

In FP, data is immutable, meaning it cannot be changed once created. Instead, new versions are created.

```javascript
const numbers = [1, 2, 3];
const newNumbers = [...numbers, 4]; // [1, 2, 3, 4]
```

- The original `numbers` array remains unchanged.

---


### 3. First-Class and Higher-Order Functions

Functions are first-class citizens in FP, meaning they can be passed as arguments, returned, or assigned to variables. Higher-order functions operate on other functions.

```javascript
function greet(name) {
    return `Hello, ${name}`;
}

function higherOrder(fn, value) {
    return fn(value);
}

console.log(higherOrder(greet, "Alice")); // Hello, Alice
```

---


### 4. Avoiding Side Effects

A side effect occurs when a function modifies something outside its scope, such as a global variable or DOM element. Avoiding side effects ensures code predictability.

```javascript
let count = 0;

function increment() {
    count++; // Side effect: modifies external variable
}
```

- FP encourages writing functions that do not rely on or alter external states.

---


### 5. Function Composition

Function composition combines smaller functions to build more complex functionality.

```javascript
const toUpperCase = str => str.toUpperCase();
const exclaim = str => `${str}!`;

const shout = str => exclaim(toUpperCase(str));
console.log(shout("hello")); // HELLO!
```

- Composed functions are modular and reusable.

---


## Benefits of Functional Programming

1. **Predictable Code**: Pure functions make behavior easy to reason about.
2. **Easier Testing**: Functions without side effects are simple to test.
3. **Reusable Code**: Small, independent functions are easier to reuse.
4. **Maintainability**: Immutable data and predictable logic reduce bugs.

---


## Common Functional Programming Methods in JavaScript

### 1. `map()`
Transforms each element in an array.

```javascript
const numbers = [1, 2, 3];
const doubled = numbers.map(num => num * 2); // [2, 4, 6]
```

---


### 2. `filter()`
Filters elements in an array based on a condition.

```javascript
const numbers = [1, 2, 3, 4];
const evenNumbers = numbers.filter(num => num % 2 === 0); // [2, 4]
```

---


### 3. `reduce()`
Reduces an array to a single value by applying a function to each element.

```javascript
const numbers = [1, 2, 3, 4];
const sum = numbers.reduce((acc, curr) => acc + curr, 0); // 10
```

---


