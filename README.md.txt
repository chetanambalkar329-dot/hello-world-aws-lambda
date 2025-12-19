# Hello World AWS Lambda

This project is a simple AWS Lambda function using Python.

## Description
- AWS Lambda (Python 3.10)
- Integrated with API Gateway
- Returns "Hello World from AWS Lambda!"

## Lambda Code

```python
def lambda_handler(event, context):
    return {
        'statusCode': 200,
        'body': 'Hello World from AWS Lambda!'
    }
