
# Reading Notes

# Class 19 - AWS: Events

## 1. Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server

[Resource](https://en.wikipedia.org/wiki/Observer_pattern)

The Observer Pattern

## 2. List the AWS Database offerings and talk about the pros and cons of each

[Resource](https://blog.gurock.com/event-driven-application-architectures/)

Creating unit tests for asynchronous functions requires a different approach to test design. In an asynchronous environment, calls happen in response to a message. The message needs to be published to a message queue, pulled by a service and then processed. Then the result needs to be published to yet another queue to an interested party. 

## 3. What’s the difference between a FIFO and a standard queue?

[Resource](https://aws.amazon.com/about-aws/whats-new/2016/11/amazon-sqs-introduces-fifo-queues-with-exactly-once-processing-and-lower-prices-for-standard-queues/#:~:text=FIFO%20queues%20have%20essentially%20the,being%20received%20by%20message%20consumers.)

FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing. FIFO queues provide additional features that help prevent unintentional duplicates from being sent by message producers or from being received by message consumers

## 4. How can the server be assured a message was properly received?

[Resource](https://docs.aws.amazon.com/sns/latest/dg/sns-topic-attributes.html)

Logging message delivery status helps provide better operational insight, such as the following:

-Knowing whether a message was delivered to the Amazon SNS endpoint.

-Identifying the response sent from the Amazon SNS endpoint to Amazon SNS.

-Determining the message dwell time (the time between the publish timestamp and just before handing off to an Amazon SNS endpoint).



## Document the following Vocabulary Terms

- **Serverless API** - Sits between the backend services of your API and your API’s users, handling the HTTP requests to your API endpoints and routing them to the correct backends. [Resource](https://www.serverless.com/amazon-api-gateway)

- **Triggers** - Triggers are events that occur in an application that invoke functions listening to those events

- **Dynamo vs Mongo** - Pub/Sub is an asynchronous messaging service that decouples services that produce events from services that process events.  [Resource](https://cloud.google.com/pubsub/docs/overview)

- **Dynamoose vs Mongoose** - Pub/Sub is an asynchronous messaging service that decouples services that produce events from services that process events.  [Resource](https://cloud.google.com/pubsub/docs/overview)


## Preview

1. Which 3 things had you heard about previously and now have better clarity on? Ive heard of AWS, but never used it before

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo? Interested in learning more about AWS SNS and SQS process

3. What are you most excited about trying to implement or see how it works? Implementing AWS SNS and SQS


