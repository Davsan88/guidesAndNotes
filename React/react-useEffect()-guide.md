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


