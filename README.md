# Course Application for the course: "Serverless en Español con AWS y Serverless Framework"

_Infrastructure as code framework used_:  Serverless Framework
_AWS Services used_: AWS Lambda, API Gateway, SQS, DynamoDB

## Summary of the demo

I have learned in this course:

- How to build a simple serverless application with AWS components and Serverless Framework

This demo is part of a video posted in FooBar Serverless channel. You can check the video to see the whole demo.

Important: this application uses various AWS services and there are costs associated with these services after the Free Tier usage - please see the AWS Pricing page for details. You are responsible for any AWS costs incurred. No warranty is implied in this example.

## Requirements
- Serverless Framework already installed and configured
- NodeJS 22.x installed

## Deploy this demo

We will be using Serverless Framework and make sure you are running the latest version.

Deploy the project to the cloud:

```
serverless deploy
```

To delete the app:

```
serverless remove
```

## Images

### Structure
![](https://github.com/kekosoftware/curso_serverless/blob/main/images/estructura_app.png)

### Create an order
![](https://github.com/kekosoftware/curso_serverless/blob/main/images/post_create_order.png)

### Get the order information
![](https://github.com/kekosoftware/curso_serverless/blob/main/images/get_order.png)