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
