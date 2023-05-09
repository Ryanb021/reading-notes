# Read 27

# useState() Hook

### Summarize the five steps of thinking in react.

- Step 1: Break The UI Into A Component Hierarchy
- Step 2: Build A Static Version in React
- Step 3: Identify The Minimal (but complete) Representation Of UI State
- Step 4: Identify Where Your State Should Live
- Step 5: Add Inverse Data Flow

### What is one reason a local variable isn’t sufficient for managing a React component?

- Local variables don’t persist between renders and changes to local variables won’t trigger renders

### What is the argument to the useState hook, and what are the two parts of its return array?

- useState is React Hook that allows you to add state to a functional component. It returns an array with two values: the current state and a function to update it. The Hook takes an initial state value as an argument and returns an updated state value whenever the setter function is called.

### How can Component A access state from Component B?

- To use the same state in several components, you have to:

    - Lift the state up to the closest common ancestor.  
    - Pass down the state variable and the function to update this state in the props. 
