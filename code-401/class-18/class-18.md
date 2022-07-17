Readings: AWS: API, Dynamo and Lambda
=====================================

Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

Reading
-------

[AWS API Gateway Overview](https://www.serverless.com/amazon-api-gateway)

1.  What is Amazon API Gateway?

    ```
    Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests.
    ```

2.  Why is Amazon API Gateway an important part of the Serverless ecosystem?

    ```
    Within the Serverless ecosystem, API Gateway is the piece that ties together Serverless functions and API definitions. Being able to trigger the execution of a Serverless function directly in response to an HTTP request is the key reason why API Gateway is so valuable in Serverless setups: it enables a truly serverless architecture for web applications. When using API Gateway together with other AWS services, it’s possible to build a fully functional customer-facing web application without maintaining a single server yourself.
    ```

3.  How does API Gateway integrate with other AWS services?

    ```
    Many AWS services support integration with Amazon API Gateway, including:

    AWS Lambda: run Lambda functions to generate HTTP API responses.
    AWS SNS: publish SNS notifications when an HTTP API endpoint is accessed.
    Amazon Cognito: provide authentication and authorization for your HTTP APIs.
    ```


[AWS API Gateway](https://aws.amazon.com/api-gateway/)

1.  What are the some benefits of using Amazon API Gateway?

    ```
    Efficient API development
    Performance at any scale
    Cost savings at scale
    Easy monitoring
    Flexible security controls
    RESTful API options
    ```

2.  What two API types might you choose from?

    ```
    1. RESTful APIs

    2. WEBSOCKET APIs
    ```


[AWS DynamoDB Guide](https://www.dynamodbguide.com/what-is-dynamo-db/)

1.  What is DynamoDB?

    ```
    hosted NoSQL database
    ```


2.  Under what circumstances would you recommend DynamoDB over MongoDB?

    ```
    When you want a low-touch operations model and connectivity with security is an important consideration.
    ```


[AWS DynamoDB](https://aws.amazon.com/dynamodb/)

1.  Explain to a non-technical friend how DynamoDB works.

    ```
    a database-as-a-service model that auto-scales and comes with connectivity and security in the box.
    ```



[Dynamoose](https://dynamoosejs.com/getting_started/Introduction)

1.  What is Dynamoose?

    ```
    Dynamoose is a modeling tool for Amazon's DynamoDB.
    ```

2.  What are some key features of Dynamoose?

    ```
    Type safety
    High level API
    Easy to use syntax
    Ability to transform data before saving or retrieving documents
    Strict data modeling (validation, required attributes, and more)
    Support for DynamoDB Transactions
    Powerful Conditional/Filtering Support
    Callback & Promise support
    ```
