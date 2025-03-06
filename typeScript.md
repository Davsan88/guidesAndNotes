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


