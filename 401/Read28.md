# Read 28

## Component Lifecycle / useEffect Hook

### What is the main intended use case for the useEffect hook?

- Placing useEffect inside the component lets us access the count state variable (or any props) right from the effect. We don't need a special API to read it — it's already in the function scope.

### How does the effect’s logic interact with the component?

- The code inside useeffect will run, when the component first mount, and the code will run again when the dependencies change. It runs after React has updated the DOM to reflect any changes made to the component’s state or props.

### What is the importance of the return value from the effect’s logic function?

- Return a cleanup function with cleanup code that disconnects from that system. It is more like a remove event listeners. The cleanup function is called when the component is unmounted, or when the effect is run again with new dependencies. The cleanup function is used to clean up any resources used by the effect, such as event listeners or timers. It’s important to return a cleanup function if the effect sets up any long-lived resources to avoid memory leaks.
