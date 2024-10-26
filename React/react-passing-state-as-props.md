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
