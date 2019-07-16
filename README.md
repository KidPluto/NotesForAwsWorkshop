# NotesForAwsWorkshop
**Near Real-time Serverless Data Processing on AWS** workshop event 
* Taking place on Tuesday, July 16, 2019 in Boston. 
* [Agenda](https://pages.awscloud.com/NAMER-event-T3-Near-Real-time-Serverless-Data-Processing-on-AWS-Boston-2019-reg.html?mkt_tok=eyJpIjoiTkRFME1EVXpZelkxTW1FdyIsInQiOiJJemlUYXkyOGs4a0lDWW4ydzJ4aloxRURTYVM5QmFQRVhJOWpjbWdXODB2RHBwTGhaZVhuTWJuRjVsVVwvXC85anc1WmJwWnNmdzRUY1ZxZmNtS1Y5R1RPV0NCcjd2cGxWVFVWRmtDXC9MRzdhd2FmeXlxdTZNMzM3VmlsSVBBQ3NpVEdHYTBrTWZtXC9mVmZwWUFHcUdQMkZRPT0ifQ%3D%3D#Agenda)

Recommended: Completion of the 
* [Amazon API Gateway, AWS Lambda, and Amazon DynamoDB Labs](https://email.awscloud.com/rT0z0M06dZlOIkTax0jD0t0) and 
  * https://72dbc9lx8l.execute-api.us-east-1.amazonaws.com/prod
  * curl https://72dbc9lx8l.execute-api.us-east-1.amazonaws.com/prod/system=system01
* [AWS Lambda Foundations](https://www.aws.training/learningobject/wbc?id=27197&mkt_tok=eyJpIjoiTkRFME1EVXpZelkxTW1FdyIsInQiOiJJemlUYXkyOGs4a0lDWW4ydzJ4aloxRURTYVM5QmFQRVhJOWpjbWdXODB2RHBwTGhaZVhuTWJuRjVsVVwvXC85anc1WmJwWnNmdzRUY1ZxZmNtS1Y5R1RPV0NCcjd2cGxWVFVWRmtDXC9MRzdhd2FmeXlxdTZNMzM3VmlsSVBBQ3NpVEdHYTBrTWZtXC9mVmZwWUFHcUdQMkZRPT0ifQ%3D%3D) free online courses prior to attending this event 

Setting up AWS CLI on work laptop

* Followed the steps on this page to install Homebrew, Pip and Python3: 

  * https://docs.python-guide.org/starting/install3/osx/

* Did this to install awscli

  * `pip3 install awscli --upgrade --user`

* Then had to `aws configure`

# Workshop

* About 50 people

# Serverless Party Parrot

* Slolom
* Toy parrot, Rasberry Pi, seven AWS services

# Alien Attack

* https://serverless.alienattack.ninja/
* Static web serving: Route53 (DNS), CloudFront (CDN), S3 (Storage)
* Security: IAM, Cognito (integrate with AD / LDAP / email / ...), 
  * RBAC - Role Based Access Control
* Injest & Consume: API Gateway 
  * Others: Kafka or IoT Gateway
  * AWS others: Kinessi Data Systems, IoT Core, AppSync



