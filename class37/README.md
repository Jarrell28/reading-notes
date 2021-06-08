
# Reading Notes

# Class 37 - Redux - Combined Reducers

## 1. Why choose Redux instead of the Context API for global state?

Redux is better for larger applications where there are high-frequency state updates. [Reource](https://www.codehousegroup.com/insight-and-inspiration/tech-stream/using-redux-and-context-api)

## 2. What is the purpose of a reducer?
Evaluates the type of action and creates a new state

## 3. What does an action contain?
Contains a object with a type and payload

## 4. Why do we need to copy the state in a reducer?
To avoid directly mutating state

## Document the following Vocabulary Terms

- **immutable state** - An immutable value or object cannot be changed, so every update creates new value, leaving the old one untouched.[Resource](https://blog.logrocket.com/immutability-in-react-ebe55253a1cc/)

- **time travel in redux** - Using the Redux Devtools Extentsion, you are able to travel back to previous versions of the application

- **action creator** - A function that returns an object with a type and payload

- **reducer** - a pure function that takes an action and the previous state of the application and returns the new state. [Resource](https://www.pluralsight.com/guides/how-to-write-redux-reducer#:~:text=In%20Redux%2C%20a%20reducer%20is,state%20based%20on%20that%20action.)
  
- **dispatch** - Dispatch is a function that dispatches an action to the Redux store


