# Read 19

# AWS: Events

## What is the difference betweeen SQS and SNS?

- SNS is typically used for applications that need realtime notifications, while SQS is more suited for message processing use cases. SNS does not persist messages - it delivers them to subscribers that are present, and then deletes them. In comparison, SQS can persist messages (from 1 minute to 14 days).

## What are some use cases for both SNS and SQS?

- Messages can be delivered to applications that require immediate notification of an event, and also persisted in an SQS queue for other applications to process at a later time. You can also combine SNS and SQS to ensure end-to-end message ordering.

## Describe how to use SQS and SNS in a “fanout” pattern.

- By using SNS and SQS together, messages can be delivered to applications that require immediate notification of an event, and also persisted in an SQS queue for other applications to process at a later time. 

## Explain how “push notifications” work, using SNS.

- Simple Notification Service (SNS) sends notifications two ways, A2A and A2P. A2A provides high-throughput, push-based, many-to-many messaging between distributed systems, microservices, and event-driven serverless applications.

## How might a large scale, distributed application make use of a Queue system like SQS?

- Simple Queue Service (SQS) lets you send, store, and receive messages between software components at any volume, without losing messages or requiring other services to be available.
