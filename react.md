# Intro to React

React is a declarative, efficient, and flexible JavaScript library for building user interfaces. It allows developers to create large web applications that can change data without reloading the page.

## What's JSX

JSX stands for JavaScript XML. It allows you to write HTML in React and is a syntax extension for JavaScript. JSX makes it easier to write and add HTML in React.

## JSX Elements

A JSX element is defined with tags, very similar to HTML. It can either represent HTML tags or user-defined components.

- Example:
  ```jsx
  const element = <h1>Hello, world!</h1>;
  ```

  ## Attributes In JSX

JSX elements can use attributes just like HTML, including classes, ids, and data-* attributes.

- Example:
  ```jsx
  const element = <img src="logo.png" className="logo" />;
  ```

## Nested JSX

JSX elements can be nested inside each other to create complex layouts.

- Example:
  ```jsx
  const element = (
    <div>
      <h1>Title</h1>
      <p>This is a paragraph.</p>
    </div>
  );
  ```

## JSX Outer Elements

When returning JSX elements from a component or including them in a variable, there must be only one outermost element.

- Example:
  ```jsx
  const element = (
    <div> {/* This div is the outer element */}
      <h1>Welcome</h1>
      <h2>To React</h2>
    </div>
  );
  ```

## Rendering JSX

To render JSX into the DOM, React uses the `ReactDOM.render()` method.

- Example:
  ```jsx
  ReactDOM.render(element, document.getElementById('root'));
  ```

  







# Advance React
## class vs className
## Self-Closing Tags
## JavaScript In Your JSX In Your JavaScript
## Curly Braces in JSX
## Variables in JSX
## Variable Attributes in JSX
## Event Listeners in JSX
## JSX Conditionals: If Statements That Don't Work
## JSX Conditionals: If Statements That Do Work
## JSX Conditionals: The Ternary Operator
## JSX Conditionals: &&
## .map in JSX
## Keys
## React.createElement
