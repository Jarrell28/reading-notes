# Reading Notes

# Class 17 - AWS: API, Dynamo and Lambda

## 1. What are serverless functions?

Conventionally, serverless functions are single-purpose, programmatic functions that are hosted on managed infrastructure. These functions, which are invoked through the Internet, are hosted and maintained by cloud computing companies. The engineering teams within those companies ensure that the serverless functions have near-perfect uptime, redundant instances around the world, and scale to any incoming network request volume. [Resource](https://www.pubnub.com/blog/what-is-a-serverless-function/)

## 2.If you were to create a system that emulated Lambda functions, how would you do it?

Lambda functions fire when certain events occur within an application. So in order to implement this I would create a event driven application which I would then be able to define events that Lambda functions react to.

## 3. Describe how a CDN works

The goal of the CDN is to reduce latency – the delay between submitting a request for a web page and the web page fully loading on your device – by reducing the physical distance that the request has to travel. CDNs store a cached version of your website content in multiple geographical locations around the world, which are known as “points of presence” (PoPs). These PoPs will contain their own caching servers and will be responsible for delivering that content in the user’s location. [Resource](https://www.akamai.com/us/en/cdn/what-is-a-cdn.jsp)


## Document the following Vocabulary Terms

- **Serverless Functions** - Single-purpose, programmatic functions that are hosted on managed infrastructure. [Resouse](https://www.pubnub.com/blog/what-is-a-serverless-function/)

- **Cloud Storage** -Cloud storage is a cloud computing model that stores data on the Internet through a cloud computing provider who manages and operates data storage as a service. [Resource](https://aws.amazon.com/what-is-cloud-storage/)

- **CDN** - A CDN (Content Delivery Network) is a highly-distributed platform of servers that helps minimize delays in loading web page content by reducing the physical distance between the server and the user. [Resource](https://www.akamai.com/us/en/cdn/what-is-a-cdn.jsp)


## Preview 

1. Which 3 things had you heard about previously and now have better clarity on? API Gateways, Dynamo DB

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? API Gateways, Serverless functions

3. What are you most excited about trying to implement or see how it works? Excited to see how API Gateways work and the benefits
