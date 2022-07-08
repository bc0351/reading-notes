# Readings: AWS: Events

Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## Reading
[AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

1. What is the difference betweeen SQS and SNS?

    ```
    SNS is a distributed publish-subscribe service.

    SQS is distributed queuing service.
    ```
2. What are some use cases for both SNS and SQS?

    ```
    SNS:  - You would like to be able to publish and consume batches of messages.
          - You would like to allow same message to be processed in multiple ways.
          - Multiple subscribers are needed.

    SQS:  - You need a simple queue with no particular additional requirements.
          - Decoupling two applications and allowing parallel asynchronous processing.
          - Only one subscriber is needed.
    ```

[AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)

1. Describe how to use SQS and SNS in a “fanout” pattern.

  ```
  messages can be published to an SNS topic with SQS queues as subscribers.
  ```

2. Explain how “push notifications” work, using SNS.

    ```
    lambda event handler.
    ```


[SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)

1. How might a large scale, distributed application make use of a Queue system like SQS?

    ```
    through the use of load balancers
    ```

## Bookmark and Review

[SNS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)

[SQS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)
