# AWS: Events

**1. Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server**
API Gateway and Lambdas manage backend RESTful routes and CRUD functions like a server does, but are not servers since they are run in AWS. An ExpressJS Server also handles back end routes, but runs on a PORT on your computer and therefore is a full server.

**2. List the AWS Database offerings and talk about the pros and cons of each**
- Aurora -- 
    best for: SaaS apps like ERP, CRM, and eCommerce
- Redshift --
    best for: Large-scale data warehouses and data migrations, analytics
- DynamoDB --
    best for: Mobile and web apps, gaming, IoT
- ElastiCache --
    best for: Caching, chat, BI and analytics, session store, gaming leaderboards
- Neptune --
    best for: Fraud detection, social networking, knowledge graphs, recommendation engines
- DocumentDB --
    best for: Content management, catalogs, user profiles
- TimeStream --
    best for: IoT applications, DevOps, industrial telemetry
- Quantum Ledger Database --
    best for: Systems of record, financial transactions, supply chain data
    [Ref](https://www.jeffersonfrank.com/insights/choosing-an-aws-database)


**3. What’s the difference between a FIFO and a standard queue?**
FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing and ensure that the order in which messages are sent and received is strictly preserved.
[Ref](https://medium.com/awesome-cloud/aws-difference-between-sqs-standard-and-fifo-first-in-first-out-queues-28d1ea5e153)

**4. How can the server be assured a message was properly received?**
Amazon SNS stores each message published across geographically-separated data centers. If a subscribed system isn't available, Amazon SNS executes a message delivery retry policy.[Ref](https://aws.amazon.com/sns/?whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc)

## Vocab
- **Serverless API:**
Within the Serverless ecosystem, API Gateway is the piece that ties together Serverless functions and API definitions. Being able to trigger the execution of a Serverless function directly in response to an HTTP request is the key reason why API Gateway is so valuable in Serverless setups: it enables a truly serverless architecture for web applications. When using API Gateway together with other AWS services, it’s possible to build a fully functional customer-facing web application without maintaining a single server yourself.
- **Triggers:** a Lambda resource or a resource in another service that you configure to invoke your function in response to lifecycle events, external requests, or on a schedule. [Ref](https://docs.aws.amazon.com/lambda/latest/dg/lambda-invocation.html)
- **Dynamo vs Mongo:** DynamoDB is a proprietary NoSQL database by Amazon that supports key-value and document data offered via the Amazon Web Services.
MongoDB is a general-purpose, document-based distributed NoSQL database. [Ref](https://www.bmc.com/blogs/mongodb-vs-dynamodb/)
- **Dynamoose vs Mongoose:**
    - DynamoDB is fully managed and Mongo is not.  Both are noSQL db's. [Ref](https://www.xplenty.com/blog/dynamodb-vs-mongodb-differences/)

## Preview
**1. Which 3 things had you heard about previously and now have better clarity on?** 
the many AWS db's and what their benefits are.
**1. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?** 
more about the other AWS db's
**1. What are you most excited about trying to implement or see how it works?**
checking out the other db's.

## Additional Resources
- [SQS & SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)
- [AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)