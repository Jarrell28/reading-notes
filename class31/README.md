
# Reading Notes

# Class 31 - Hooks API

## 1. Why do we not need more .html pages in a multi-page React app?

We use a Router Library to determine which "component/page" should be displayed based on the url instead of directing to an actual html file.

## 2. If we wanted a component to show up on every page, where would we put it and why?
We would put it inside <BrowserRouter /> and outside a <Route /> because anything outside of <Route /> will show on every page. And we also need it to be inside of <BrowserRouter/> because our application needs to be wrapped by it.

## 3. What does props.children contain?
props.children contains any elements/components that are passed as children in the parent component wrapper.


## Document the following Vocabulary Terms

- **composition** - React Composition is a development pattern based on React's original component model where we build components from other components using explicit defined props or the implicit children prop.[Resource](https://formidable.com/blog/2021/react-composition/)

- **Children / Child Components** - Children allow you to pass components as data to other components, just like any other prop you use. [Resource](https://buildwithreact.com/article/component-children)

- **Hash Routing** - A <Router> that uses the hash portion of the URL (i.e. window.location.hash) to keep your UI in sync with the URL. [Resource](https://reactrouter.com/web/api)

- **Link Routing** - Provides declarative, accessible navigation around your application. [Resource](https://reactrouter.com/web/api)

## Preview 

1. Which 3 things had you heard about previously and now have better clarity on? Hooks API, state hooks, useEffect hook

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? Hooks API

3. What are you most excited about trying to implement or see how it works? Implementing an application using all functional components



