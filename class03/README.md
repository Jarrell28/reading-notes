# Reading Notes

# Class 02 - Express

## 1.What's the difference between PUT and PATCH?

Resource - https://blog.segunolalive.com/posts/restful-api-design-%E2%80%94-put-vs-patch/

**PUT** - This HTTP method is used to make major updates to a resource. When making an update to the resource, the PUT request will update each property of the resource even if the values are the same.

**PATCH** - This HTTP method is used to make minor updates to a resource. When making an update, this will only update a portion of the resource.

## 2. Provide links to 3 services/tools that allow you to mock an API for development

1. [MockServer](https://www.mock-server.com/#what-is-mockserver)

2. [Postman](https://www.postman.com/features/mock-api/)

3. [Mockend](https://mockend.com/)

## 3. Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?

**Swagger** - According to Swagger documentation, in the event of an unsuccessful API call, it will return a 400 for a Bad request, 401 for authorization issues, or 404 for information Not Found

**APIDocJS** - According to APIDocJS documentation, in the event of an unsuccessful API call, it will return a 404 for information Not Found

## 4. Compare and Contrast SOAP and REST

Resource - https://www.soapui.org/learn/api/soap-vs-rest-api/

**SOAP** 

- SOAP uses XML format for transmitting data

- Can be sent over any protocol such as HTTP, SMTP, TCP, or JMS

- Requires additional configuration for setup, mostly used in enterprise environments

- SOAP is function driven


**REST**

- REST primarily uses JSON format for transmitting data, but can also us a variety of different formats such as XML and YAML

- HTTP is required for REST

- Fast and lightweight

- REST is data driven

## Document the following Vocabulary Terms

- **Web Server** - A web server is computer software and underlying hardware that accepts requests via HTTP, the network protocol created to distribute web pages, or its secure variant HTTPS. [Wikipedia](https://en.wikipedia.org/wiki/Web_server)

- **Express** - Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications. [Express](https://expressjs.com/)

- **Routing** -  Routing is the mechanism by which requests (as specified by a URL and HTTP method) are routed to the code that handles them. [OReilly](https://www.oreilly.com/library/view/web-development-with/9781491902288/ch14.html#:~:text=Routing%20is%20the%20mechanism%20by,the%20path%20%2Ffoo%2Fabout.)

- **WRRC** - A cycle of requests and responses that flow between clients and servers. [Medium](https://medium.com/@jen_strong/the-request-response-cycle-of-the-web-1b7e206e9047)

## Preview

1. Which 3 things had you heard about previously and now have better clarity on? TDD, CI/CD, Express Middleware

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? I am hoping to learn more about TDD, Express Middleware implementation,  CI/CD best practices 

3. What are you most excited about trying to implement or see how it works? The most I am excited about is TDD. I feel this is crucial in the development space
