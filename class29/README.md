
# Reading Notes

# Class 29 - Routing

## 1. Do child components have direct access to props/state from the parent?

If the parent passes it to the child component, then yes.

## 2. When a component “wraps” another component, how does the child component’s output get rendered?
By return props.children on the Main Component

## 3. Can a component, such as <Content />, which is a child also be used as a standalone component elsewhere in the application?
Yes

## 4. What trick can a parent use to share all props with it’s children

Can use the spread operator to pass all props. [Resource](https://medium.com/coding-at-dawn/how-to-pass-all-props-to-a-child-component-in-react-bded9e38bb62#:~:text=If%20you%20happen%20to%20know,child%20components%2C%20DisplayAllProps%20and%20ChildComponent%20.)

## Document the following Vocabulary Terms

- **props.children** - Allows a component to render JSX and other components as it's children

- **composition** - React Composition is a development pattern based on React's original component model where we build components from other components using explicit defined props or the implicit children prop.[Resource](https://formidable.com/blog/2021/react-composition/)

## Preview 

1. Which 3 things had you heard about previously and now have better clarity on? Browser Router, history, Route

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? Context API, hooks, dynamic forms

3. What are you most excited about trying to implement or see how it works? Using Context API to manage App state


