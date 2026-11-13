# -aws-lambda-serverless-project-
AWS Lambda and API Gateway Serverless Project
# AWS Lambda & Serverless Project

### Project Overview
This project demonstrates a serverless application built using AWS Lambda and Amazon API Gateway.

The objective is to create and deploy a serverless HTTP API that executes an AWS Lambda function and returns a JSON response.

### AWS Services Used
- AWS Lambda
- Amazon API Gateway
- HTTP API
- AWS CloudWatch

### Architecture
Client (Browser) → API Gateway (HTTP API) → AWS Lambda → JSON Response

### Configuration Details
- Lambda Function: ashish-serverless-function
- API Name: ashish-serverless-api
- API Route: GET /
- Stage: $default
- Auto Deploy: Enabled
- AWS Region: ap-south-1 (Mumbai)

### Live API Endpoint
https://b90a3yyy03.execute-api.ap-south-1.amazonaws.com

### Sample API Response
```json
{
  "message": "Hello Ashish!",
  "project": "AWS Lambda Serverless",
  "status": "Success"
}
```

### Project Outcome
Successfully created, integrated, deployed, and tested a serverless API using AWS Lambda and Amazon API Gateway.

### Author
Ashish Pokale
