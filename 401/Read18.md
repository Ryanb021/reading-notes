# Read 18

## Readings: AWS: API, Dynamo and Lambda

## What is Amazon API Gateway?

- A fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale. 

## Why is Amazon API Gateway an important part of the Serverless ecosystem?

- Helps you manage traffic to your backend systems by allowing you to set throttling rules based on the number of requests per second for each HTTP method in your APIs.

## How does API Gateway integrate with other AWS services?

- Mock integration, where API Gateway serves as an integration endpoint to respond to a method request. The Lambda custom integration is a special case of the AWS integration, where the integration endpoint corresponds to the function-invoking action of the Lambda service.

## What is DynamoDB?

- DynamoDB is an Amazon Web Services database system that supports data structures and key-valued cloud services. It allows users the benefit of auto-scaling, in-memory caching, backup and restore options for all their internet-scale applications using DynamoDB.

## Under what circumstances would you recommend DynamoDB over MongoDB?

- DynamoDB will allow a maximum of just 400 KB, while MongoDB has a limit of 16 MB. If you need to store big objects with DynamoDB, AWS recommends using another service, such as S3. Bear in mind that while this solution can work, it does so at the cost of reduced performance.

## Explain to a non-technical friend how DynamoDB works.

- It's like a Dinosaur. That's how I would explain it to my non-technical friend.

## What is Dynamoose?

- Dynamoose is a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose, which means if you are coming from Mongoose the syntax will be very familiar.

## What are some key features of Dynamoose?

- Type safety
- High level API
- Easy to use syntax
- DynamoDB Single Table Design Support
- Ability to transform data before saving or retrieving items
- Strict data modeling (validation, required attributes, and more)
- Support for DynamoDB Transactions
- Powerful Conditional/Filtering Support
- Callback & Promise support
- AWS Multi-region support
