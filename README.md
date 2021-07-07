# AWS (Amazon Web Services)

<img src="https://user-images.githubusercontent.com/69857268/124731664-12193c00-df30-11eb-9dbc-9aafc842a385.png" alt="AWS" width="300px"/> 



# Lambda-DynamoDB-Postman
Call an API from postman, trigger lamnda, get data from dynamodb

## DynamoDB
 Create a table in dynamodb.
## API Gateway
* Add the Resources and methods.
* Stage the events.
## IAM
* Create the role.
* Attach the policies like -
    * AWSLambdaBasicExecutionRole
    * AmazonDynamoDBFullAccess
    * CloudWatchLogsFullAccess
## Lambda Function
* Create function in lambda.
* Attach the IAM role.
* Attach the api gateway created.
* Copy the code (index.js) to lambda function.
* Deploy the function

## Postman
* After the stage in API Gateway, get the URL.
* Paste it in the Postman.
* Change the API URL to the corresponding paths and verify them
* Insert the values.
* It gets inserted in the DynamoDB table.

Thus the goal is achieved. ✅
Happy Coding..😀
