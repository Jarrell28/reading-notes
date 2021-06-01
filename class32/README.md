
# Reading Notes

# Class 32 - Custom Hooks

## 1. What does a component’s lifecycle refer to?

There are different lifecycle methods that React provides at different phases of a component’s life. React automatically calls the responsible method according to the phase in which the component is. These methods give us better control over our component and we can manipulate them using these methods. [Resource](https://www.freecodecamp.org/news/how-to-understand-a-components-lifecycle-methods-in-reactjs-e1a609840630/)

## 2. Why do you sometimes need to “wrap” functions in useCallback when called from within useEffect
If the function called inside useEffect makes the component re-render, it could cause an infinite loop. Using useCallback prevents this. [Resource](https://medium.com/@infinitypaul/reactjs-useeffect-usecallback-simplified-91e69fb0e7a3)

## 3. Why are functional components preferred over class components?
They are easier to read, less code to write and easier to implement. [Resource](https://djoech.medium.com/functional-vs-class-components-in-react-231e3fbd7108)

## 4. What is wrong with the following code?

![image](https://user-images.githubusercontent.com/33704616/120403235-69146b80-c309-11eb-8357-46410a06124d.png)

The for loop should be inside the useEffect callback with renderedItems.pushinside the for loop

## Document the following Vocabulary Terms

- **state hook** - Allows you to add state to function components.[Resource](https://blog.logrocket.com/a-guide-to-usestate-in-react-ecb9952e406c/)

- **effect hook** - Allows you to run functions when something in the functional component updates/renders.

- **reducer hook** - The useReducer is a hook  used to manage the state of the application. It is very similar to the useState hook, just more complex. [Resource](https://adhithiravi.medium.com/what-is-the-usereducer-hook-6274af633541)

## Preview 

1. Which 3 things had you heard about previously and now have better clarity on? Custom hooks, Reducer hooks

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? custom hooks, reducer hooks

3. What are you most excited about trying to implement or see how it works? Implementing Reducer hooks




