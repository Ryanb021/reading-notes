# Read 37

# Redux - Combined Reducers

### Why create multiple reducers?

- Multiple slice reducers can respond to the same action, independently update their own slice as needed, and the updated slices are combined into the new state object. Because this pattern is so common, Redux provides the combineReducers utility to implement that behavior.

### How would you combine multiple reducers?

- How do you combine multiple reducers?
You define multiple reducers to handle different pieces of your application's state, then compose these reducers together into one root reducer. The root reducer is then passed into the Redux createStore() method. In order to let us combine multiple reducers together, Redux provides the combineReducers() method.

### How will you manage state as an immutable object? why?

- An immutable value or object cannot be changed, so every update creates new value, leaving the old one untouched. For example, if your application state is immutable, you can save all the state objects in a single store to easily implement functionality to undo and redo.

### combineReducers is a utility function to simplify the most common use case when writing ___ _____ .

- Redux reducers.

### Explain how combineReducers assembles the new state tree.

- In order to assemble the new state tree, combineReducers will call each slice reducer with its current slice of state and the current action, giving the slice reducer a chance to respond and update its slice of state if needed.

### How would you define initial state in an app using combineReducers?

- There are two main ways to initialize state for your application. The createStore method can accept an optional preloadedState value as its second argument. Reducers can also specify an initial value by looking for an incoming state argument that is undefined , and returning the value they'd like to use as a default.

### Why will you want to split your reducing functions as your app becomes more complex?

- Scalability: As your application grows and becomes more complex, separating your JavaScript code from your React code can help you manage that complexity. By breaking your application down into smaller, more manageable pieces, you can avoid bloated files and keep your codebase more scalable.

### The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.

- combineReducers, createStore

### What is a popular convention when naming reducers?

-  Use descriptive names that reflect the state slice they handle.
