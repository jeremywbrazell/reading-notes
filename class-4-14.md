# Event Driven Architecture

**1. What’s the difference between a FIFO and a standard queue?**
Standard queues provide at-least-once delivery, which means that each message is delivered at least once.

FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it. Duplicates are not introduced into the queue.
[Ref](https://aws.amazon.com/sqs/faqs/)

**1. How can the server be assured a message was properly received?**
it guarantees a response from the client that the message has been received

**1. What classic design pattern is best represented by event driven programming?**
Observer pattern
[Ref](https://en.wikipedia.org/wiki/Observer_pattern)

**1. How do you test an event driven system?**
1. Ensure supporting topics exist
1. Start the application under test (“application” here could mean Kafka Streams, Kafka connectors, Samza, etc.)
1. Send some input events
1. Wait until the application has finished processing the test input
1. Assert that it looks right
[Ref](https://www.confluent.io/blog/testing-event-driven-systems/)

## Vocab
**FIFO Queue:** a queue that operates on a first-in, first-out (FIFO) principle. This means that the request (like a customer in a store or a print job sent to a printer) is processed in the order in which it arrives. A first-come, first-served line is the most common type of queue that we join in our everyday lives and is generally accepted as the fairest way to operate a queue.
[Ref](https://queue-it.com/queue-first-in-first-out/)

**Pub/Sub:** stands for Publisher/Subscriber, allows services to communicate asynchronously, with latencies on the order of 100 milliseconds.

Pub/Sub is used for streaming analytics and data integration pipelines to ingest and distribute data. It is equally effective as messaging-oriented middleware for service integration or as a queue to parallelize tasks.
[Ref](https://cloud.google.com/pubsub/docs/overview)

## Preview
**1. Which 3 things had you heard about previously and now have better clarity on?**
The difference between FIFO and a standard queue, what an observer pattern is, and what Pub/Sub is
**1. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
AWS, SNS, SQS Systems

**1. What are you most excited about trying to implement or see how it works?**
The breadth of AWS and why it is so widely used.

## Additional Resources
[SNS vs SQS Comparison](https://www.youtube.com/watch?v=mXk0MNjlO7A)




