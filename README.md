# NotesForAwsWorkshop
**Near Real-time Serverless Data Processing on AWS** workshop event 
* Taking place on Tuesday, July 16, 2019 in Boston. 
* [Agenda](https://pages.awscloud.com/NAMER-event-T3-Near-Real-time-Serverless-Data-Processing-on-AWS-Boston-2019-reg.html?mkt_tok=eyJpIjoiTkRFME1EVXpZelkxTW1FdyIsInQiOiJJemlUYXkyOGs4a0lDWW4ydzJ4aloxRURTYVM5QmFQRVhJOWpjbWdXODB2RHBwTGhaZVhuTWJuRjVsVVwvXC85anc1WmJwWnNmdzRUY1ZxZmNtS1Y5R1RPV0NCcjd2cGxWVFVWRmtDXC9MRzdhd2FmeXlxdTZNMzM3VmlsSVBBQ3NpVEdHYTBrTWZtXC9mVmZwWUFHcUdQMkZRPT0ifQ%3D%3D#Agenda)

Recommended: Completion of the 
* [Amazon API Gateway, AWS Lambda, and Amazon DynamoDB Labs](https://email.awscloud.com/rT0z0M06dZlOIkTax0jD0t0) and 
  * https://72dbc9lx8l.execute-api.us-east-1.amazonaws.com/prod
  * `curl https://72dbc9lx8l.execute-api.us-east-1.amazonaws.com/prod/getconfig?system=system01`
* [AWS Lambda Foundations](https://www.aws.training/learningobject/wbc?id=27197&mkt_tok=eyJpIjoiTkRFME1EVXpZelkxTW1FdyIsInQiOiJJemlUYXkyOGs4a0lDWW4ydzJ4aloxRURTYVM5QmFQRVhJOWpjbWdXODB2RHBwTGhaZVhuTWJuRjVsVVwvXC85anc1WmJwWnNmdzRUY1ZxZmNtS1Y5R1RPV0NCcjd2cGxWVFVWRmtDXC9MRzdhd2FmeXlxdTZNMzM3VmlsSVBBQ3NpVEdHYTBrTWZtXC9mVmZwWUFHcUdQMkZRPT0ifQ%3D%3D) free online courses prior to attending this event 

Setting up AWS CLI on work laptop

* Followed the steps on this page to install Homebrew, Pip and Python3: 

  * https://docs.python-guide.org/starting/install3/osx/

* Did this to install awscli

  * `pip3 install awscli --upgrade --user`

* Then had to `aws configure`

# Workshop

* About 50 people
* Two different stickers for Lambda, which I think is a squarrel.  One of them was wearing glasses.  So the most important way of getting you service to succed is to have a cute animal icon.
* The Cloud 9 IDE is not integrated with AWS 

# Serverless Party Parrot

* Slolom
* Toy parrot, Rasberry Pi, seven AWS services

# Alien Attack

* https://serverless.alienattack.ninja/
* http://lab.alienattack.ninja
* **Static web serving**: AWS Route53 (DNS), AWS CloudFront (CDN), AWS S3 (Storage)
* Security: AWS IAM, Cognito (integrate with AD / LDAP / email / ...), 
  * RBAC - Role Based Access Control
* **Injest & Consume**: AWS API Gateway to AWS Kinesis (real-time data stream processing) to talk to AWS Cognito
  * API Gateway is able to check that the data is good, unlike Kinesis or IoT Core
  * Others: Kafka or IoT Gateway
  * AWS others: Kinesis Data Systems, IoT Core, AppSync
* **Processing**:  AWS Kinesis Data Firehose, AWS Lambda
  * AWS Fargate is different from AWS ECS how?
  * AWS ECS on EC2 (gives you more control) vs AWS Fargate
  * AWS others: AWS Kinesis Data Analytics, AWS Fargate (runs containers)
* **Storage layer**: AWS Systems Manager, AWS DynamoDB
* **Push notifications** (to start the game): AWS API Gateway 
* https://github.com/fabianmartins/alienattack.workshop



