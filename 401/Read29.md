# Read 29

# Advanced State with Reducers

### What is the motivation for adding a reducer?

- A reducer is a function that is able to process our message, our Action. A reducer takes the existing state and applies the message on it. The end result is a new state. A reducer typically operates on a slice of state.

### What are actions in the context of a reducer? How are they different than setting state directly? 

- Reducers are basically pure JS functions which take in the previous state and an action and return the newly updated state. A reducer is a pure function that takes an action and the previous state of the application and returns the new state. The action describes what happened and it is the reducer's job to return the new state based on that action.

### What common list operation is useReduce named for, and why?

- By convention, it is common to give it a string type that describes what happened, and pass any additional information in other fields.

### When should you switch from useState to useReducer?

- If you're using useState to manage complex states with a large number of properties, or if your component is frequently rendering, it can have an impact on performance. In such cases, it may be better to use useReducer instead of useState.
