# Reading Notes

# Class 41 - Redux - React Native

## 1. Compare and Contrast Redux Toolkit with Redux “Ducks”

**Redux:**
- Requires a lot of boilerplate to configure store
- Must separately install commonly used dependencies
- Must write immutable code to update state

**Redux Toolkit:**
- Redux Toolkit comes with additional libraries such as redux thunk, immer.js, and redux devtools extension using configureStore()
- Able to write mutable code when updating state
- Configuring store is simplified
- Creating reducers and actions are simplified

## 2. What is the principle advantage of Redux Toolkit

It allows us to write more efficient code, speed up the development process, and automatically apply the best-recommended practices. It was mainly created to solve the THREE MAJOR ISSUES with Redux:

Configuring a Redux store is too complicated
Have to add a lot of packages to build a large scale application
Redux requires too much boilerplate code which makes it cumbersome to write efficient and clean code.

[Resource](https://www.geeksforgeeks.org/what-is-redux-toolkit-and-why-it-is-more-preferred/)

## Document the following Vocabulary Terms

- **redux toolkit slices** - A function that accepts an initial state, an object full of reducer functions, and a "slice name", and automatically generates action creators and action types that correspond to the reducers and state. [Resource](https://redux-toolkit.js.org/api/createSlice)

- **namespace** - Namespaces are used to organize code into logical groups and to prevent name collisions that can occur especially when your code base includes multiple libraries. [Resource](https://docs.microsoft.com/en-us/cpp/cpp/namespaces-cpp#:~:text=A%20namespace%20is%20a%20declarative,code%20base%20includes%20multiple%20libraries.)

