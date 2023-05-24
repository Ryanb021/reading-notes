# Read 38

# Redux - Asynchronous Actions

### Why use Redux middleware?

- Redux Middleware allows you to intercept every action sent to the reducer so you can make changes to the action or cancel the action. Middleware helps you with logging, error reporting, making asynchronous requests, and a whole lot more.

### Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.

- Eventhandler will dispatch action to the middleware and middleware will send it to the API and wait for the data. once the middleware received the data, it will dispatch it to the store.
- 
### How are we accommodating async in our Redux app?

- Just like with a normal action, we first need to handle a user event in the application, such as a click on a button. Then, we call dispatch() , and pass in something, whether it be a plain action object, a function, or some other value that a middleware can look for.

### Why would you need redux-thunk middleware?

- Thunk is a logical concept in programming where you deal with a function that is primarily used to delay the calculation or evaluation of any operation. Redux Thunk acts as a middleware that will return you a function instead of an object while calling through the action creators.

### Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.

- Funtion

### Describe how any return value from the inner thunk function will be made available.

- Any return value from the inner function will be available as the return value of dispatch itself.
