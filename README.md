# Build-a-Basic-Web-Application
Following AWS Tutorial https://aws.amazon.com/getting-started/hands-on/build-web-app-s3-lambda-api-gateway-dynamodb/?e=gs2020&amp;p=fullstack

Services Used:
AWS Amplify: host static content
Amazon API Gateway: host API 
AWS Lambda: host serverless functions
Amazon DynamoDB

![AWS Serivce](https://d1.awsstatic.com/webteam/getting_started/GSRC%202020%20updates/full-stack%20amplify%20console%20arch%20diagram%20module%205.8d82fc2a7b47b307dfcefb6fa5f364e8c24426bc.png)

## Module 1
[Module 1](https://aws.amazon.com/getting-started/hands-on/build-web-app-s3-lambda-api-gateway-dynamodb/module-one/?e=gs2020&p=build-a-web-app-intro)

Created index.html, zipped it up.
Launched [AWS Amplify](https://aws.amazon.com/amplify/console/).  Chose "getting started", deploy from file (could have done from github?).

Deployed: https://dev.d2s4liugez0u7n.amplifyapp.com/

## Module 2
[Module 2](https://aws.amazon.com/getting-started/hands-on/build-web-app-s3-lambda-api-gateway-dynamodb/module-two/?e=gs2020&p=build-a-web-app-one)

Created Lambda function using the [AWS Lambda Console](https://console.aws.amazon.com/lambda/).

## Module 3
[Module 3](https://aws.amazon.com/getting-started/hands-on/build-web-app-s3-lambda-api-gateway-dynamodb/module-three/?e=gs2020&p=build-a-web-app-two)

Create API using the [AWS API Gateway Console](https://console.aws.amazon.com/apigateway/)

Deployed to: https://9yln1rp345.execute-api.us-east-1.amazonaws.com/dev/

Test: https://console.aws.amazon.com/apigateway/home?region=us-east-1#/apis/9yln1rp345/resources/75vz585cmh/methods/POST

## Module 4
[Module 4](https://aws.amazon.com/getting-started/hands-on/build-web-app-s3-lambda-api-gateway-dynamodb/module-four/)

Create table using [AWS DynamoDB Console](https://console.aws.amazon.com/dynamodb/home)

Resource (ARN): arn:aws:dynamodb:us-east-1:424106097484:table/HelloWorldDatabase]

Modify lambda function from module 2 to utilize database

## Module 5
[Module 5](https://aws.amazon.com/getting-started/hands-on/build-web-app-s3-lambda-api-gateway-dynamodb/module-five/)

Wire web application to the API from above
