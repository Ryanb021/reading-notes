# Read 39

# Redux - Additional Topics

### What concerns are addressed by Redux Toolkit?

- "Configuring a Redux store is too complicated"
- "I have to add a lot of packages to get Redux to do anything useful"
- "Redux requires too much boilerplate code"

### What does configureStore() do?

- configureStore sets up a well-configured Redux store with a single function call, including combining reducers, adding the thunk middleware, and setting up the Redux DevTools integration. It also is easier to configure than createStore , because it takes named options parameters.

### How would I use createSlice()?

- createSlice is a higher-order function that accepts the slice name (e.g. token, user, todos), a set of reducers, and returns a single reducer along with the action creators for that reducer. The goal of createSlice is to reduce the boilerplate required to add data to redux the canonical way.

### What is Mobx?

- MobX is a battle-tested library that makes state management simple and scalable by transparently applying functional reactive programming.

### How does MobX make it “impossible” to produce an inconsistent state?

- MobX makes state management simple again by addressing the root issue: it makes it impossible to produce an inconsistent state. The strategy to achieve that is simple: Make sure that everything that can be derived from the application state, will be derived.

### How would we build a reactive user interface?

- The observer HoC wrapper from the mobx-react-lite package fixes that by basically wrapping the React component in autorun. This keeps the component in sync with the state. This is conceptually not different from what we did with the report before.
