## Hi there 👋

Hi, I’m a cloud developer focused on building scalable, serverless applications using AWS Lambda and API Gateway. This repository showcases how I design and implement event-driven systems that are efficient, secure, and cost-effective.

At the heart of my approach is event-driven architecture. I use AWS services like Lambda, API Gateway, S3, DynamoDB, EventBridge, and Step Functions to build loosely coupled workflows that respond to events in real time. Whether it’s a REST API request, a file upload, or a scheduled job, each component reacts to specific triggers, allowing the system to scale automatically and remain highly available.

A key advantage of this architecture is cost-efficiency. Since AWS Lambda charges only for compute time, and scales without the need for managing infrastructure, I’m able to build production-grade applications with minimal operational overhead. This setup eliminates idle server costs and simplifies deployment, making it ideal for both startups and enterprise use cases.

Security is also a top priority in every project I work on. I follow the principle of least privilege by tightly controlling IAM roles and permissions. Where applicable, I use API keys, JWTs, and AWS Cognito for authentication and authorization. I also apply input validation and rate limiting to protect APIs against abuse.

This repository reflects how I design serverless systems that are not only scalable and maintainable, but also secure and aligned with AWS best practices. Each service and resource is defined as infrastructure-as-code (using tools like AWS SAM or the Serverless Framework), making the projects easy to deploy, test, and extend.
