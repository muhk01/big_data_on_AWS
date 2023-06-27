# AWS Athena

In this case, is usecase to read stored csv files in S3, then create table in athena which the data is sourced from bucket S3 and then query like SQL RDBMS.
In query define a source path which is all attached-csv in this repository, then dont forget to define 
```
ResultConfiguration={'OutputLocation': output_location}
```
this is where the result for each query stored.

## Requirements.

1. Install the Boto3 library: Make sure you have Boto3 installed on your system. You can install it using pip:
```
pip install boto3
```
2. Set up AWS Credentials: Boto3 requires AWS credentials to authenticate and authorize your access to S3. You can either set environment variables or create a configuration file to provide your AWS Access Key ID and Secret Access Key. in this example is using access key configured in IAM Console. but it can also be setup by AWS CLI
```
aws configure
```

