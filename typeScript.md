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

