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
