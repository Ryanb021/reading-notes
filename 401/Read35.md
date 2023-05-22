# Read 35

# Application State with Redux

### What is the first principle of Redux?

- Single Source of Truth. This means that we should only store one state object on our application, no more, no less.

### what is a store and what do we use our reducers for within that store?

- A store is an immutable object tree in Redux. A store is a state container which holds the application's state. Redux can have only a single store in your application. Whenever a store is created in Redux, you need to specify the reducer.

### Name three Redux store methods given to us by createStore and describe their use.

- reducer (Function): A reducing function that returns the next state tree, given the current state tree and an action to handle.

- [preloadedState] (any): The initial state. You may optionally specify it to hydrate the state from the server in universal apps, or to restore a previously serialized user session. If you produced reducer with combineReducers, this must be a plain object with the same shape as the keys passed to it. Otherwise, you are free to pass anything that your reducer can understand.

- [enhancer] (Function): The store enhancer. You may optionally specify it to enhance the store with third-party capabilities such as middleware, time travel, persistence, etc. The only store enhancer that ships with Redux is applyMiddleware().

### Explain to a non-technical recruiter what combineReducers() does and why it is useful.

- Helps you organize your reducers to manage their own slices of state, similar to how you would have different Flux Stores to manage different state. With Redux, there is just one store, but combineReducers helps you keep the same logical division between reducers.
