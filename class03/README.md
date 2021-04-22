# Reading Notes

# Class 03 - Express REST API

## 1.Name 3 real world use cases where you’d want to change the request with custom middleware

Resource - https://www.freecodecamp.org/news/what-is-middleware-with-example-use-cases/

- User Authentication
- API Security - Can use middleware as a proxy to conceal our authentication server's URL
- Exposing Public API - Can implement a middleware that only exposes some of the endpoints and redirects the requests to our actual API

## 2. True or false: The route handler is middleware?

Resource - https://expressjs.com/en/guide/routing.html

True - In this example we can see route handlers being used as middleware 

```
var cb0 = function (req, res, next) {
  console.log('CB0')
  next()
}

var cb1 = function (req, res, next) {
  console.log('CB1')
  next()
}

var cb2 = function (req, res) {
  res.send('Hello from C!')
}

app.get('/example/c', [cb0, cb1, cb2])
```

## 3. In what ways can a middleware function end the process and send data to the browser?

Resource - https://www.geeksforgeeks.org/express-js-res-end-function/

Using res.end([data]), you can end the request process and send data to the browser 

## 4. At what point in the request lifecycle can you “inject” middleware?

- After a request has been made from the client to the server, if configured, middleware will run after the request was made.


## 5. What can cause express to error with “Request headers sent twice, cannot start a second response”

Resource - https://github.com/mozilla/nunjucks/issues/652

-If you are attempting to send a response more than once in a route without using return for either of them.


## Document the following Vocabulary Terms

- **Middleware** - Express middleware are functions that execute during the lifecycle of a request to the Express server. [Resource](https://developer.okta.com/blog/2018/09/13/build-and-understand-express-middleware-through-examples)

- **Request Object** - The req object represents the HTTP request and has properties for the request query string, parameters, body, HTTP headers, and so on. [Resource](https://www.tutorialspoint.com/nodejs/nodejs_request_object.htm)

- **Response Object** -  The res object represents the HTTP response that an Express app sends when it gets an HTTP request. [Resource](https://www.tutorialspoint.com/nodejs/nodejs_response_object.htm#:~:text=Node.-,js%20%2D%20Response%20Object,it%20gets%20an%20HTTP%20request.)

- **Application Middleware** - Bind application-level middleware to an instance of the app object by using the app.use() and app.METHOD() functions, where METHOD is the HTTP method of the request that the middleware function handles (such as GET, PUT, or POST) in lowercase. [Resource](http://expressjs.com/en/guide/using-middleware.html)

- **Routing Middleware** - Router-level middleware works in the same way as application-level middleware, except it is bound to an instance of express.Router(). [Resource](http://expressjs.com/en/guide/using-middleware.html)

- **Test Driven Development** - Test-driven development (TDD) is a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases. [Resource](https://en.wikipedia.org/wiki/Test-driven_development)

- **Behavioral Testing** - Behavioral Driven Development (BDD) is a software development approach that has evolved from TDD (Test Driven Development). It differs by being written in a shared language, which improves communication between tech and non-tech teams and stakeholders. [Resource](https://blog.testlodge.com/what-is-bdd/)


## Preview

1. Which 3 things had you heard about previously and now have better clarity on? ES6 Classes, Middleware, TDD

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? TDD, MiddleWare, Routing architecture

3. What are you most excited about trying to implement or see how it works? TDD. I want to establish a strong foundation with writing tests
