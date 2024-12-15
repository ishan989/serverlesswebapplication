# serverlesswebapplication
Project Description:
# Serverless Greeting App

A simple serverless application that increments a view counter every time it's accessed. This project demonstrates the power of serverless architecture by leveraging AWS services like S3, CloudFront, Lambda, and DynamoDB.

## Features

- **Dynamic View Counter**: Updates the view count on each access.
- **Serverless Architecture**: Fully managed backend with no servers to maintain.
- **Global Content Delivery**: Optimized performance using CloudFront.
- **Cache Invalidation**: Handles updates to static files seamlessly.
- **Secure IAM Roles**: Implements AWS best practices for Lambda permissions.

## Architecture


- **S3**: Hosts the static files for the application.
- **CloudFront**: Distributes the application globally with low latency.
- **AWS Lambda**: Handles backend logic to increment the view counter.
- **DynamoDB**: Stores the view count using a partition key.

### Architecture Diagram

<img width="638" alt="image" src="https://github.com/user-attachments/assets/c82da4e7-1c6f-4b3c-80ed-cf3b064922d6" />

## Prerequisites

- AWS Account
- Basic knowledge of AWS services (S3, Lambda, DynamoDB, CloudFront)
- Node.js or Python installed locally (for Lambda development)
