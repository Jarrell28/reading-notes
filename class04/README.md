# Reading Notes

# Class 04 - Data Modeling

## 1.Name 3 advantages to Test Driven Development

Resource - https://www.codica.com/blog/test-driven-development-benefits/

- Better program design and higher code quality

- Code flexibility and easier maintenance

- With TDD you will get a reliable solution

## 2. In what case would you need to use beforeEach() or afterEach() in a test suite?

Resource - https://jestjs.io/docs/api#beforeeachfn-timeout

beforeEach and afterEach is best used when you want to reset some global state that will be used by many tests. Before each test, it will set the global state, and after each test it will reset the global state to be used by the next test.

## 3. What is one downside of Test Driven Development

Resource - https://www.geeksforgeeks.org/advantages-and-disadvantages-of-test-driven-development-tdd/

Some developers say that implementing TDD will extend the time it takes to develop an application. 


## 4. What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?

Resource - https://www.bestinterviewquestion.com/question/differentiate-between-es6-class-and-es5-function-constructors-sdkha4870nc#:~:text=ES6%20class%20allows%20the%20developers,being%20created%20by%20the%20developer.

- The process of inheriting a class is much simpler using ES6 Classes.


## 5. Why REST?

Resource - https://www.chakray.com/advantages-of-rest-api/

-Due to its scalability

-Due to its flexibility and portability

-Due to its independence


## Document the following Vocabulary Terms

- **functional programming** - In computer science, functional programming is a programming paradigm where programs are constructed by applying and composing functions. It is a declarative programming paradigm in which function definitions are trees of expressions that map values to other values, rather than a sequence of imperative statements which update the running state of the program.. [Resource](https://en.wikipedia.org/wiki/Functional_programming)

- **object-oriented programming (OOP)** - Object Oriented programming (OOP) is a programming paradigm that relies on the concept of classes and objects. It is used to structure a software program into simple, reusable pieces of code blueprints (usually called classes), which are used to create individual instances of objects. [Resource](https://www.educative.io/blog/object-oriented-programming)

- **Class** -  A class is an abstract blueprint used to create more specific, concrete objects. Classes often represent broad categories, like Car or Dog that share attributes. [Resource](https://www.educative.io/blog/object-oriented-programming)

- **Super** - The super keyword is used to access and call functions on an object's parent.. [Resource](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/super)

- **This** - A property of an execution context (global, function or eval) that, in non–strict mode, is always a reference to an object and in strict mode can be any value.. [Resource](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this)

- **Test Driven Development** - Test-driven development (TDD) is a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases. [Resource](https://en.wikipedia.org/wiki/Test-driven_development)

- **Jest** - Jest is a JavaScript Testing Framework with a focus on simplicity. [Resource](https://jestjs.io/)

- **Continuous Integration (CI)** - Continuous integration (CI) is the practice of automating the integration of code changes from multiple contributors into a single software project. [Resource](https://www.atlassian.com/continuous-delivery/continuous-integration)

- **REST** - A REST API (also known as RESTful API) is an application programming interface (API or web API) that conforms to the constraints of REST architectural style and allows for interaction with RESTful web services. REST stands for representational state transfer and was created by computer scientist Roy Fielding. [Resource](https://www.redhat.com/en/topics/api/what-is-a-rest-api)

- **Data Model** - an abstract model that organizes elements of data and standardizes how they relate to one another and to the properties of real-world entities. For instance, a data model may specify that the data element representing a car be composed of a number of other elements which, in turn, represent the color and size of the car and define its owner.. [Resource](https://en.wikipedia.org/wiki/Data_model)


## Preview

1. Which 3 things had you heard about previously and now have better clarity on? MongoDB, Mongoose, Nosql

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? data modeling, modular design, TDD

3. What are you most excited about trying to implement or see how it works? TDD is still what I am most exicted to learn about. Now that Databases are involved, I want to gain more experience writing tests for databases

