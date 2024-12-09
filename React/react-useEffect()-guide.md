# A Beginner's Guide to `useEffect` in React

The `useEffect` hook is one of the most important hooks in React, allowing you to perform side effects in your functional components. It replaces lifecycle methods like `componentDidMount`, `componentDidUpdate`, and `componentWillUnmount` in class components.

---


## What is a Side Effect?

Side effects are tasks that run in response to changes in your component or application. These can include:
- Fetching data from an API.
- Subscribing to a service or event listener.
- Manually updating the DOM.
- Setting up a timer.

---


## Syntax of `useEffect`

```javascript
import React, { useEffect } from 'react';

useEffect(() => {
  // Side effect logic here
  return () => {
    // Cleanup logic here (optional)
  };
}, [dependencies]);
```

- **Effect Function**: The function you pass to `useEffect`. This contains the logic for the side effect.
- **Cleanup Function (Optional)**: A function returned from the effect function, used to clean up after the effect (e.g., removing event listeners).
- **Dependency Array**: An array that specifies when the effect should run. Dependencies are variables or state values the effect depends on.

---


## Common Use Cases for `useEffect`

### 1. Running Once (on Mount)
Use an empty dependency array (`[]`) to run the effect only once when the component mounts.

```javascript
useEffect(() => {
  console.log('Component mounted');
}, []);
```

#### Example: Fetch data when the component loads.
```javascript
useEffect(() => {
  fetch('https://api.example.com/data')
    .then(response => response.json())
    .then(data => console.log(data));
}, []);
```

---


### 2. Running on State or Prop Change
Specify state or props in the dependency array to run the effect whenever those values change.

```javascript
const [count, setCount] = React.useState(0);

useEffect(() => {
  console.log(`Count changed to ${count}`);
}, [count]);
```

---


### 3. Cleanup Logic
Return a function from `useEffect` to clean up resources when the component unmounts or before the effect runs again.

#### Example: Remove an event listener.
```javascript
useEffect(() => {
  const handleResize = () => console.log('Window resized');
  window.addEventListener('resize', handleResize);

  return () => {
    window.removeEventListener('resize', handleResize);
  };
}, []);
```

---


