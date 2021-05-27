
# Reading Notes

# Class 28 - Component Composition

## 1. Can a parent component access the state of a child component?

Yes, You can access a child components state using Refs. Probably not the best idea to do it in this manner and recommended to lift state to parent from child. [Resource](https://www.geeksforgeeks.org/how-to-access-childs-state-in-react/#:~:text=In%20React%20we%20can%20access,can%20access%20the%20child's%20state.)

## 2. What can be passed along in a prop variable?
Can pass pretty much anything. Variables, arrays, objects, JSX, even components.

## 3. How can a child component “know” the state of another component?

By having App.js manage state for the other component and passing its state to the child component

## Document the following Vocabulary Terms

- **component props** - Data that is passed from a parent component to a child component.

- **component state** - Data that is managed within that component

- **application state** - Data that is globally managed by App.js so child components can have access to other child component's state

## Preview 

1. Which 3 things had you heard about previously and now have better clarity on? props.children, Lifecycle methods

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? Context API, hooks, dynamic forms

3. What are you most excited about trying to implement or see how it works? Using Context API to manage App state

