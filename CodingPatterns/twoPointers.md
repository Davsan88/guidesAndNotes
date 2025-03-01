# **🔍 What Is the Two Pointers Pattern?**

Imagine you have an **array** (or sometimes a **string**) and you want to solve a problem by examining **elements from different ends or positions simultaneously**. The **Two Pointers Pattern** uses **two indices (pointers)** that move through the data structure at **different speeds or directions**. 

This approach is particularly useful when the **data is sorted** or when you're **looking for pairs** or **certain relationships between elements**.

---

## **📝 Key Idea**
### **📌 Dual Indices:**
- Use **two pointers**:
  - One **starting at the beginning** (`left`).
  - One **starting at the end** (`right`).

### **📌 Movement Based on Conditions:**
- Adjust the pointers based on a **condition** (e.g., if the **current sum is too low** or **too high**) until:
  - They **meet**.
  - A **solution is found**.

### **📌 Efficiency:**
- This technique allows you to process the **array in a single pass**.
- It **reduces the time complexity** from **O(n²) (nested loops) → O(n) (linear time).**

---


## **🚀 Why Use Two Pointers?**

### **Problem Example: Find a Pair with a Given Sum in a Sorted Array**

#### **❌ Naive Approach**
- **Idea**:
  - For every element in the array, **iterate through all the remaining elements** to see if a pair sums to the target.

- **Time Complexity**:
  - **O(n²)** due to **nested loops**.

#### **✅ Two Pointers Approach**
1️⃣ **Step 1**:
   - **Place one pointer (`left`) at the beginning**.
   - **Place one pointer (`right`) at the end**.

2️⃣ **Step 2**:
   - **Calculate the sum** of the elements at these pointers.

3️⃣ **Step 3**:
   - If the **sum equals the target**, you've found your pair. 🎯
   - If the **sum is less than the target**, move the **left pointer right** (to increase the sum).
   - If the **sum is greater than the target**, move the **right pointer left** (to decrease the sum).

- **Time Complexity**:
  - **O(n)** → Each element is **examined at most once**.

---




