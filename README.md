# voyzu-planned-architecture
Planned architecture for upcoming 'Voyzu' Proof of Concept (PoC)

### domain management

- Route 53
- Certificate Manager

### identity management and security

- Cognito
- IAM

### data storage

- DynamoDb
- Relational Database Service - MySQL.  Note  - when Aurora Serverless is released this is planned to be used instead of MySQL

### web application layer

- Lambda
- API Gateway
- Simple Email Service

### Web UI

- [AdminLTE](https://github.com/almasaeed2010/AdminLTE)
- Jquery
- Various open source components e.g. [bootstrap-table](https://github.com/wenzhixin/bootstrap-table)

### Application Integration

- Simple Notification Service (SNS)

### Devops / Infrastructure as Code

- Cloudwatch
- Cloud Formation

### deployment pipeline

- Codebuild
- Lambda
- S3
