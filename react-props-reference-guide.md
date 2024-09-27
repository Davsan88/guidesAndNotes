# Working with Props and Destructuring in React

In React, **props** (short for properties) allow components to receive data from their parent component. This concept makes components dynamic, flexible, and reusable. By passing props, you can create components that render different data depending on what is passed to them. Additionally, **destructuring** props leads to cleaner and more readable code by extracting properties directly, avoiding repetitive access to the props object.

## Key Concepts:
- **Props** allow components to be **reusable** and **dynamic**.
- Props are passed to components as **attributes in JSX**.
- Props are accessed inside a component via the **props object**.
- **Destructuring** allows extracting props directly as variables for cleaner code.

## Step-by-Step Guide: Working with Props and Destructuring

### 1. Passing Props from Parent to Child
In the parent component, you can pass data to a child component by using attributes in JSX:

```jsx
function App() {
  return (
    <div>
      <Joke setup="Why did the chicken cross the road?" punchline="To get to the other side!" />
    </div>
  );
}
```

In this example, `setup` and `punchline` are the props being passed to the `Joke` component.
