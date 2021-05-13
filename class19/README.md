
# Reading Notes

## Class 19 - AWS: Events

### 1. Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server

They are similiar in the fact that you are defining routes and the callback functions when those routes are hit in both technologies.

### 2. List the AWS Database offerings and talk about the pros and cons of each

[Resource](https://aws.amazon.com/products/databases/)

There are many different AWS Databases. RDS, DynamoDB, ElastiCache, Neptune, Amazon QLDB, Amazon DocumentDB, Amazon Keyspaces, Amazon Timestream.

Pros and Cons of DynamoDB:

**Pros:**

- Great performance even with large scale applications.

- We don't need to manage any backend servers, everything is a one-click solution in their dashboard.

- Support great reliability and scalability while supporting ACID transactions.

**Cons:**
- The costs can be huge if the resource is not monitored properly. We had to crank it down during off-peak hours and again increase the throughput during high usage intervals.

- While the time of usage, DynomoDB did not support different region backup. The backups were only within the same region.

- Best suited for key-value type of operations only. Won't work particularly great for relational operations.


### 3. What’s the difference between a FIFO and a standard queue?

[Resource](https://aws.amazon.com/about-aws/whats-new/2016/11/amazon-sqs-introduces-fifo-queues-with-exactly-once-processing-and-lower-prices-for-standard-queues/#:~:text=FIFO%20queues%20have%20essentially%20the,being%20received%20by%20message%20consumers.)

FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing. FIFO queues provide additional features that help prevent unintentional duplicates from being sent by message producers or from being received by message consumers

### 4. How can the server be assured a message was properly received?

[Resource](https://docs.aws.amazon.com/sns/latest/dg/sns-topic-attributes.html)

Logging message delivery status helps provide better operational insight, such as the following:

- Knowing whether a message was delivered to the Amazon SNS endpoint.

- Identifying the response sent from the Amazon SNS endpoint to Amazon SNS.

- Determining the message dwell time (the time between the publish timestamp and just before handing off to an Amazon SNS endpoint).



### Document the following Vocabulary Terms

- **Serverless API** - Sits between the backend services of your API and your API’s users, handling the HTTP requests to your API endpoints and routing them to the correct backends. [Resource](https://www.serverless.com/amazon-api-gateway)

- **Triggers** - Triggers are events that occur in an application that invoke functions listening to those events

- **Dynamo vs Mongo:** [Resource](https://www.xplenty.com/blog/dynamodb-vs-mongodb-differences/#:~:text=DynamoDB%20as%20an%20integrated%20AWS,and%20has%20fewer%20size%20restrictions.)

  1. MongoDB is vendor agnostic, Open Source, and can be deployed anywhere. DynamoDB is only available on AWS.

  2. DynamoDB is a fully managed AWS service, MongoDB can be self installed or fully managed with MongoDB Atlas.

  3. DynamoDB as an integrated AWS service makes it easier to develop end to end solutions.

  4. DynamoDB uses tables, items and attributes, MongoDB uses JSON-like documents.

  5. DynamoDB supports limited data types and smaller item sizes; MongoDB supports more data types and has fewer size restrictions.

- **Dynamoose vs Mongoose** - They are essentially the same, but have some small differences with how they handle retrieval and storage of data using methods.


