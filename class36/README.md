
# Reading Notes

# Class 36 - Application State with Redux

## 1. What are the advantages of storing tokens in “Cookies” vs “Local Storage”

It allows you to produce global variables that can be accessed from anywhere in the application. This is very useful for Login features where you have to keep track of the current user. [Resource](https://www.loginradius.com/blog/async/react-context-api/)

## 2. Explain 3rd party cookies.
No, it must be inside the provider wrapper

## 3. How do pixel tags work?

Accessing Current User, Themes, Shopping cart

## Document the following Vocabulary Terms

- **cookies** - Application state that is accessible by any component
- **authorization** - provides a way to pass data through the component tree without having to pass props down manually at every level 
- **access control** - a component that as it's names suggests provides the state to its children. [Resource](https://www.loginradius.com/blog/async/react-context-api/)
- **conditional rendering** -  a component that consumes and uses the state. [Resource](https://www.loginradius.com/blog/async/react-context-api/)





