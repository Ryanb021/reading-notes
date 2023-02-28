# Read 02

## React: Component Lifecycle Events

## What are component lifecycle events?[Source](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.

![React](https://user-images.githubusercontent.com/120413183/221799343-79e1d800-5098-4ae0-8d02-f2267cabc67a.png)

## What is the very first thing to happen in the lifecycle of React?

*Mounting* - When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase.

## Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

- constructor
- render
- React Updates
- componentDidMount
- componentWillUnmount

## componentDidMount

This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().

setState() can be called here, but it should be used sparingly, because it will cause a rerender, which can lead to perfomance issues.

## What types of things can you pass in the props?

You can pass any JavaScript value through props, including objects, arrays, and functions. Props is like HTML attributes. [source](https://beta.reactjs.org/learn/passing-props-to-a-component)

## What is the big difference between props and state?

While both hold information that influences the output of render, they are different in one important way: 
props get passed to the component (similar to function parameters)
whereas state is managed within the component (similar to variables declared within a function). [source](https://reactjs.org/docs/faq-state.html#:~:text=While%20both%20hold%20information%20that,variables%20declared%20within%20a%20function).)

## When do we re-render our application?

Re-render happens when React needs to update the app with some new data. Usually, this happens as a result of a user interacting with the app or some external data coming through via an asynchronous request or some subscription model. [source](https://www.developerway.com/posts/react-re-renders-guide)

## What are some examples of things that we could store in state?
-objects
-data
