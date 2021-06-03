
# Reading Notes

# Class 34 - <Login/> and <Auth />

## 1. Why is the Context API useful?

It allows you to produce global variables that can be accessed from anywhere in the application. This is very useful for Login features where you have to keep track of the current user. [Resource](https://www.loginradius.com/blog/async/react-context-api/)

## 2. Can a component outside of a provider get its context?
No, it must be inside the provider wrapper

## 3. What are some common use cases for using the Context API?
Accessing Current User, Themes, Shopping cart

## 4. Describe “Context Hell”
Context Hell is when you have multiple context providers that are nested. [Resource](https://dev.to/alfredosalzillo/the-react-context-hell-7p4)

![image](https://user-images.githubusercontent.com/33704616/120714894-70fb1980-c489-11eb-8f02-208653c77fe9.png)


## Document the following Vocabulary Terms

- **global state** - Application state that is accessible by any component
- **global context** - provides a way to pass data through the component tree without having to pass props down manually at every level 
- **provider** - a component that as it's names suggests provides the state to its children. [Resource](https://www.loginradius.com/blog/async/react-context-api/)
- **consumer** -  a component that consumes and uses the state. [Resource](https://www.loginradius.com/blog/async/react-context-api/)

## Preview 

1. Which 3 things had you heard about previously and now have better clarity on? Context API

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? Context API, Redux, Reducers

3. What are you most excited about trying to implement or see how it works? Implementing Context API 





