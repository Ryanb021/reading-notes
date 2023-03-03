# Read 05

## Putting it all together

## What is the single responsibility principle and how does it apply to components?

Is a technique for deciding if you should create a new function or object. That is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

## What does it mean to build a ‘static’ version of your application?

A version that takes your data model and renders the UI but has no interactivity and requires a lot of typing and no thinking.

## Once you have a static application, what do you need to add?

Interactivity.

## What are the three questions you can ask to determine if something is state?

- Is it passed in from a parent via props? If so, it probably isn’t state.
- Does it remain unchanged over time? If so, it probably isn’t state.
- Can you compute it based on any other state or props in your component? If so, it isn’t state.

## How can you identify where state needs to live?

- Identify every component that renders something based on that state.
- Find a common owner component (a single component above all the components that need the state in the hierarchy).
- Either the common owner or another component higher up in the hierarchy should own the state.
- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.
[Source](https://reactjs.org/docs/thinking-in-react.html)

## What is a “higher-order function”?

Functions that operate on other functions, either by taking them as arguments or by returning them.

## Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

Boolean.

## Explain how either map or reduce operates, with regards to higher-order functions

The map method transforms an array by applying a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array, but its content will have been mapped to a new form by the function. Reduce builds a value by repeatedly taking a single element from the array and combining it with the current value.
[Source](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

