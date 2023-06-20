# AWS DynamoDB

Integration AWS DynamoDB with BOTO3 Python
In this example is used to Query existing NoSQL table, and to create, insert, and query new table.

To integrate Amazon DynamoDB with the Boto3 library, you need to follow these steps:

1. Install the Boto3 library: Make sure you have Boto3 installed on your system. You can install it using pip:
```
pip install boto3
```
2. Set up AWS Credentials: Boto3 requires AWS credentials to authenticate and authorize your access to DynamoDB. You can either set environment variables or create a configuration file to provide your AWS Access Key ID and Secret Access Key. in this example is using access key configured in IAM Console. but it can also be setup by AWS CLI
```
aws configure
```
