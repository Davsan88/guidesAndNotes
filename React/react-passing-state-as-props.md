# Passing State as Props in React

Passing state variables as props allows child components to access and display data managed by their parent components. This is a common practice in React for building dynamic and reusable components.


## 1. Passing State Variables to Child Components

When you have a state variable in a parent component, you can pass it to a child component as a prop.

```jsx
// ParentComponent.jsx
import React, { useState } from 'react';
import ChildComponent from './ChildComponent';

function ParentComponent() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <ChildComponent number={count} />
      <button onClick={() => setCount(count + 1)}>Increment</button>
    </div>
  );
}

export default ParentComponent;
```

In this example, `ParentComponent` manages the `count` state and passes it to `ChildComponent` via the `number` prop.


## 2. Receiving State Props in Child Components

The child component receives the state variable as a prop and can use it in its rendering logic.

```jsx
// ChildComponent.jsx
import React from 'react';

function ChildComponent({ number }) {
  return (
    <div>
      <p>The count is: {number}</p>
    </div>
  );
}

export default ChildComponent;
```

Here, `ChildComponent` receives the `number` prop and displays it.


## 3. Updating State from Child Components

If you need the child component to update the parent's state, you can pass the state updater function as a prop.


```jsx
// ParentComponent.jsx
function ParentComponent() {
  const [count, setCount] = useState(0);

  const increment = () => setCount(prevCount => prevCount + 1);

  return (
    <div>
      <ChildComponent number={count} increment={increment} />
    </div>
  );
}
```

```jsx
// ChildComponent.jsx
function ChildComponent({ number, increment }) {
  return (
    <div>
      <p>The count is: {number}</p>
      <button onClick={increment}>Increment</button>
    </div>
  );
}
```


## 4. Practical Example: Passing State in the Meme Generator App

In the Meme Generator app, you might have a parent component that manages the state and passes it to child components.
