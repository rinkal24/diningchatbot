# Dining Chatbot

Customer Service is a core service for a lot of businesses around the world and it is getting disrupted at the moment by Natural Language Processing-powered applications.
A serverless, microservice-driven web application named as Dining Concierge chatbot that sends you restaurant suggestions given a set of preferences that you provide the chatbot with through conversation.
It consists of the following components:
 - AWS S3 bucket
 - API Gateway
 - AWS Lambda
 - Amazon Lex
 - SQS
 - SNS
 - Cognito
 - Dynamo DB
 - Elastic Search
 - Yelp API
 
 ## Architecture
 
 ![alt text](https://github.com/rinkal24/diningchatbot/blob/main/architecture.PNG)
 
 ## Response received in the end via mail: 
 {
  "Type" : "Notification",
  "MessageId" : "92427051-a2dd-5289-a5d1-284554b56eaf",
  "TopicArn" : "arn:aws:sns:us-east-1:772764957281:sns_dining",
  "Message" : "Hello! For new york, we recommend :1-India Kitchen located at 493 9th Ave with 263 reviews and average rating of 4.0stars\n2-Ashoka Indian Restaurant located at 489 Columbus Ave with 228 reviews and average rating of 4.5stars\n",
  "Timestamp" : "2020-10-29T16:56:08.807Z"
  }
