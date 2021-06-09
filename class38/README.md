
# Reading Notes

# Class 37 - Redux - Combined Reducers

## 1. How granular should your reducers be?

It should be as granular as possible as this allows you to maintain and scale your applications easily.

## 2. Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched

Pro - This allows you to update different sections of your application simultaneously and reduces some amount of code in your application.

## 3. Name a strategy for preventing the above
Have descriptive action types to prevent any chance of a duplicate

## Document the following Vocabulary Terms

- **store** - Holds the state of your application. [Resource](https://redux.js.org/api/store)

- **combined reducers** - turns an object whose values are different reducing functions into a single reducing function you can pass to createStore. [Resource](https://redux.js.org/api/combinereducers)

