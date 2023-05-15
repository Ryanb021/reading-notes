# Read 31

# Context API

### Summarize the five principles for structuring state.

- 1. Group Related State
If two state variables change together, it is a good practice to combine them into a single state variable.
- 2. Avoid Duplicate in State
When the same data is duplicated between multiple state variables or within nested objects, it is difficult to keep in sync
- 3. Avoid Redundant State
If you can calculate some information from the component’s props or its existing state variables during rendering, you should not put that information into that component’s state.
- 4. Avoid Contradiction in State
When the state is structured in a way that several pieces of state may contradict, you probably have a chance to make mistakes. Try to avoid this.
- 5. Avoid Deeply Nested State
Deeply hierarchical state is not very easy to update, hence it is a best practice to make the state structure flat.

### What problem do Contexts aim to solve?

- The main idea of using the context is to allow your components to access global data and re-render when that global data is changed. Context solves the props drilling problem: when you have to pass down props from parents to children. You can hold inside the context: global state

### What is one technique to try before useContext?

- To use context in a class component, set the static contextType property of the component to the context object you created earlier. Then, access the context data using this. context. By following these steps, you can effectively use React Context to manage and share state across your components.

### What hook complements useContext for complex applications?

- useState() hook allows you create and mange a state variable that can be a simple JavaScript primitive or an object. Typically this is how you would do it.
