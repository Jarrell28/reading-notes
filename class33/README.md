
# Reading Notes

# Class 33 - Context API

## 1. Describe use cases for useMemo() and useReducer()

- useMemo can help the performance of an application by “remembering” expensive functions and preventing a re-render every time there is a change in the application. [Resource](https://www.digitalocean.com/community/tutorials/react-usememo)

- useReducer is great for managing more complicated state than you would want to manage with useState on its own. [Resource](https://daveceddia.com/usereducer-hook-examples/)

## 2. Why do custom hooks need the use prefix?
React requires this because it warns you when attempting to use custom hooks in unintended ways.

## 3. What do custom hooks usually do?
Custom Hooks provide you with reusuable functionality that you can use in multiple areas of your application.

## 4. Using any list of custom hooks, research and name one that you think will be useful in your applications

React-use seems pretty useful. It allows you to keep track of screen size, motion, animations, and dynamically adjust CSS. 

## 5. Describe how a hook that fetches API data might work
Can have a function for each of the REST methods in the API hook that performs the API call and takes in a callback argument to update a component state with the results.

## Document the following Vocabulary Terms

- **reducer** - A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. [Resource](https://css-tricks.com/understanding-how-reducers-are-used-in-redux/#:~:text=A%20reducer%20is%20a%20function,so%20that%20they%20behave%20consistently.)

## Preview 

1. Which 3 things had you heard about previously and now have better clarity on? Context API

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? Context API, Redux, Reducers

3. What are you most excited about trying to implement or see how it works? Implementing Context API 





