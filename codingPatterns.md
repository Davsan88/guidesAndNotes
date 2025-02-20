# **Essential Concepts Before Learning Coding Patterns**

To efficiently solve coding problems, it is crucial to understand **fundamental concepts** and **core principles** in **algorithm design**. These concepts will help you **recognize when and how to apply coding patterns effectively**.

---


## **1. Time & Space Complexity (Big O Notation)**

### **Why is it Important?**
- **Big O notation** helps measure how an algorithm’s performance **scales with input size**.
- It allows you to choose the **most efficient approach** for a problem.

### **Common Complexities:**
- **O(1) - Constant Time**: Execution time **does not** depend on input size.
- **O(log n) - Logarithmic Time**: The problem size is **reduced** in each step (e.g., **binary search**).
- **O(n) - Linear Time**: Execution **grows directly** with input size.
- **O(n log n) - Log-Linear Time**: Common in **efficient sorting algorithms** (*merge sort, quicksort*).
- **O(n²) - Quadratic Time**: Nested loops that process **elements in pairs**.
- **O(2ⁿ) / O(n!) - Exponential and Factorial Time**: Typically found in **brute-force solutions** and **recursion-heavy problems**.

### **Example:**
```javascript
// O(n) - Linear time (looping through an array)
function sumArray(arr) {
    let sum = 0;
    for (let num of arr) {
        sum += num;
    }
    return sum;
}

// O(1) - Constant time (direct index access)
function getFirstElement(arr) {
    return arr[0];
}
```

---


## **2. Data Structures**

### **Why are they Important?**
- Understanding **data structures** helps in **optimizing solutions** and **choosing the right approach** for a problem.

