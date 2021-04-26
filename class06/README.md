# Reading Notes

# Class 06 - Authentication

## 1. Explain what a “Singleton” is (in Computer Science terms)

Resource - https://en.wikipedia.org/wiki/Singleton_pattern

The singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system.

## 2. Explain how the Singleton pattern can be used with Node modules, specifically with classes

Resource - https://medium.com/swlh/node-js-and-singleton-pattern-7b08d11c726a

We can use the Singleton pattern by creating a Singleton class, and exporting the instance of that class. Node.Js will cache and reuse the same object each time it's required.

```
class Singleton {
    constructor() {
        this.message = 'I am an instance';
    }
}
module.exports = new Singleton();

```


## 3. If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

Going off of how express middleware works, I would need to create a function that takes in the request and response as an argument in order to be able to modify them. I would also require function similar to next() in order to interact with the request-response cycle. 


## Document the following Vocabulary Terms

- **Router Middleware** - Router middleware is middleware that only applies to certain routes in Express.

- **Dynamic Module Loading** - Dynamic loading is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory. [Resource](https://en.wikipedia.org/wiki/Dynamic_loading)

- **Singleton Pattern** -  The singleton pattern is a software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system. [Resource](https://en.wikipedia.org/wiki/Singleton_pattern)

- **CRUD -> REST Method Matches** - ![image](https://user-images.githubusercontent.com/33704616/116161480-6f377c80-a6b9-11eb-97ae-734d2a33d0c5.png)


- **Mock Testing** - Mock testing is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. [Resource](https://devopedia.org/mock-testing)



## Preview

1. Which 3 things had you heard about previously and now have better clarity on? bcrypt, authorization, authentication

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? Bearer Auth, bcrypt, best security practices

3. What are you most excited about trying to implement or see how it works? I've seen Bearer Auth many times in requests from my previous job. I am curious how this works 
