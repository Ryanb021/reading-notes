# Read 26

## Component Based UI

### What are the building blocks of a React app?

- Elements are the smallest building blocks of React apps. An element describes what you want to see on the screen. Unlike browser DOM elements, React elements are plain objects, and are cheap to create.
- 
### What is the difference between an HTML element and a React component?

- HTML is a markup language, and in modern web development, it's being used to structure websites. On the other hand, React is a library for building websites. It uses plain HTML, but on top of that, it provides a lot of handy features that add interactivity, and complex logic to websites.

### What is JSX and why do we use it?

- JSX stands for JavaScript syntax extension. It is a JavaScript extension that allows us to describe React's object tree using a syntax that resembles that of an HTML template. It is just an XML-like extension that allows us to write JavaScript that looks like markup and have it returned from a component.

### Describe the process of embedding JavaScript expressions in JSX.

- You can put any valid JavaScript expression inside the curly braces in JSX. 

### Does React or JSX have any special features for iteration or conditional logic?

- The conditional (ternary) operator is the only JavaScript operator that takes three operands: a condition followed by a question mark ( ? ), then an expression to execute if the condition is truthy followed by a colon ( : ), and finally the expression to execute if the condition is falsy.

### How does React know to respond to a user’s inputs?

- In React there is two ways to handle data, one is props and the other is state. When people first learn about these two ways that data is handle in React, it could get confusing on when and where to use them. Props allow you to pass data from a parent component to a child component.

### What word indicates that a React component manages data with a Hook?

- The rules of React Hooks clearly state: Don't call Hooks inside loops, conditions, or nested functions. Instead, always use Hooks at the top level of your React function. React Hooks need to be called in the same order each time the component renders.

### How can two react components share data?

- Parent to child component.
- Child to parent component.
- Sharing data between sibling.
- Sharing data between not related components.

### What are the three steps of refreshing a React UI?

- To refresh a page in React, you don't need React, just plain JavaScript. You need to call window. location. reload which will trigger a full page reload.

### How do you trigger updates to a component after the initial render?

- In any user or system event, you can call the method this.forceUpdate() , which will cause render() to be called on the component, skipping shouldComponentUpdate() , and thus, forcing React to re-evaluate the Virtual DOM and DOM state.
- 
### Does React recreate DOM nodes on every rerender?

- Even though React re-renders every component in the tree, it doesn't update every node in the DOM. React only updates a text node that is supposed to change visually.

### After React has updated the DOM, what still needs to happen before the user sees the change?

- A component's state can change over time; whenever it changes, the component re-renders. The change in state can happen as a response to user action or system-generated events and these changes determine the behavior of the component and how it will render.
