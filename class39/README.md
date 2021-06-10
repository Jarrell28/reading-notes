# Reading Notes

# Class 39 - Redux - Additional Topics

## 1. What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?

To make the async call to load data when the application initially loads, in React it would be to make the call in componentDidMount or useEffect on initial load. 

## 2. When using a thunk/async action that dispatches the actual action, which do you export from your reducer?

Export the action that is performing async because you will be calling this action in your application.

## Document the following Vocabulary Terms

- **middleware** - Redux middleware provides a third-party extension point between dispatching an action, and the moment it reaches the reducer. People use Redux middleware for logging, crash reporting, talking to an asynchronous API, routing, and more. [Resource](https://redux.js.org/tutorials/fundamentals/part-4-store)

- **thunk** - A thunk is a function that wraps an expression to delay its evaluation. [Resource](https://github.com/reduxjs/redux-thunk)

