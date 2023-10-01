# ambe-application-codes
use for storing application codes



# For the registration form project

# Serverless Registration Form
---------------------------------

## Step 1: Create DynamoDB Table

```sh
Table Name: registration-table
Partition key: email

```

## Step 2: Create IAM Role for Lambda Function
```sh
IAM Role Name: RegistrationFormRole

Permissions:
1. CloudWatch Full Access
2. DynamoDB Full Access

```

## Step 3: Create Lambda Function

```sh
Function Name: registration-form-function
Runtime: Python 3.9

```

## Step 4: Write Lambda Function

## Step 5: Create API Gateway and Enable CORS

## Step 6: Create an S3 Bucket and  Test the Project


### Enable CORS: 

```sh
Access-Control-Allow-Origin: '*'
Access-Control-Allow-Headers: Content-Type,X-Amz-Date,Authorization,X-Api-Key,X-Amz-Security-Token
Access-Control-Allow-Methods: POST

```

## Step 7: Test the Application



## For the amazone connect project
 ## Created a customer service call center with amazon connect for a ccompany called: ambe Gadget Company
 --------------------------------------------------
youtube tutorial:
 https://www.youtube.com/watch?v=yKNb6db_d7c&list=PLGhcieJ42HtH7fksyhSnTu4mv6G1HsU9o&ab_channel=ArchitectureBytes

 ## For the Amazon lex BurgerBuddy project

 ## For the Facial Recognition project
