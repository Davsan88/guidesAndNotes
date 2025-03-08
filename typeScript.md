# 🚀 **TypeScript Guide**

**TypeScript** is a **statically typed superset** of JavaScript that enhances **code reliability, maintainability, and developer experience**. It helps **catch errors at compile-time** rather than runtime, making it a valuable tool for modern **frontend development**.

---


## 📌 **Basic Types**
TypeScript provides **strict types** for better **code safety**.

```ts
let username: string = "Jimi"; // Text values
let age: number = 30; // Numbers (integers & floats)
let isDeveloper: boolean = true; // True/false values
```
👉 **Why?** Ensures variables are assigned the correct data type, **reducing unexpected runtime errors**.

---


## **Type Inference**
If TypeScript can **infer** the type, you **don’t need to explicitly define it**.

```ts
let city = "London"; // TypeScript infers `city` as a string
```
👉 **Why?** Reduces unnecessary repetition while still **enforcing type safety**.

---


## 📌 **Defining Custom Types**
Instead of manually defining object structures every time, you can use **type aliases** or **interfaces**.

### **Type Alias**
```ts
type User = {
  id: number;
  name: string;
  isAdmin?: boolean; // Optional property
};
```
👉 **Why?** Makes code **more reusable and maintainable**.

### **Interface (Preferred for Objects)**
```ts
interface Product {
  name: string;
  price: number;
}
```
👉 **Why?** Interfaces provide a **structured blueprint for objects**, making code more **readable**.

---


## 📌 **Typing Objects & Arrays**

### **Object Type**
```ts
const user: { name: string; age: number } = { name: "Jimi", age: 30 };
```

### **Array Type**
```ts
let numbers: number[] = [1, 2, 3]; // Array of numbers
let users: User[] = [{ id: 1, name: "Alice" }]; // Array of User objects
```
👉 **Why?** Prevents **incorrect data structures**, ensuring **consistency**.

---


## 📌 **Optional & Readonly Properties**
- **`Optional (?)`** → Allows properties to be **optional**.
- **`Readonly (readonly)`** → Prevents modifying a property after assignment.

```ts
type UserProfile = {
  readonly id: number;
  name: string;
  email?: string; // Optional
};

const user: UserProfile = { id: 1, name: "David" };
user.id = 2; // ❌ Error: Cannot modify a readonly property.
```
👉 **Why?** Improves **code safety** by **preventing unintended modifications**.

---


## 📌 **Literal Types**
Restricts a variable to **specific predefined values**.

```ts
type Theme = "light" | "dark";
let userTheme: Theme = "light"; // ✅ Valid
userTheme = "blue"; // ❌ Error
```
👉 **Why?** Useful for enforcing **strict, predefined configurations**.

---


## 📌 **Unions & Intersections**

### **Union Types (`|`)**
Allows **multiple possible types**.

```ts
let input: string | number;
input = "Hello"; // ✅
input = 42; // ✅
```
👉 **Why?** Great for functions that handle **multiple input types**.

### **Intersection Types (`&`)**
Combines **multiple types into one**.

```ts
type Admin = { isAdmin: boolean };
type User = { name: string };

type AdminUser = Admin & User;
const admin: AdminUser = { name: "Alice", isAdmin: true };
```
👉 **Why?** Useful for **merging multiple data types**.

---


## 📌 **Type Narrowing**
TypeScript needs **runtime checks** to determine the **actual type**.

```ts
function printId(id: string | number) {
  if (typeof id === "string") {
    console.log(id.toUpperCase());
  } else {
    console.log(id.toFixed(2));
  }
}
```
👉 **Why?** Prevents **errors when working with multiple data types**.

---


## 📌 **Function Return Types**
Explicitly **defining the return type** improves **clarity**.

```ts
function add(a: number, b: number): number {
  return a + b;
}
```
👉 **Why?** Helps catch **unintended return values**.

### **Void (No return value)**
```ts
function logMessage(message: string): void {
  console.log(message);
}
```

---


## 📌 **Utility Types (`Partial` & `Omit`)**

### **`Partial<T>`** 
Makes all properties optional

```ts
type User = { id: number; name: string; email: string };
type PartialUser = Partial<User>;
```
👉 **Why?** Useful for **updating objects** without needing **all fields**.

### **`Omit<T, K>`** (Removes specific properties)

```ts
type UserWithoutEmail = Omit<User, "email">;
```
👉 **Why?** Helps when you need a **modified version** of an **existing type**.

---


## 📌 **Generics (Reusable Types)**
Generics allow **creating flexible, reusable components**.

