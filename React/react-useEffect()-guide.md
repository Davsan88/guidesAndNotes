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


