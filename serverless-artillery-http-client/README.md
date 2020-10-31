# serverless-artillery-http-client

## prerequisites
- Serverless Framework
  - 1.x.x (1.40.0)
    - 2.x.x seems not to be supported
      - Ref: https://dev.classmethod.jp/articles/loadtest-by-serverless-artillery
- Serverless Artillery
  - Latest (0.5.2)

## Deploy to AWS as Lambda Function
1. Setup AWS credentials on deploy machine
1. `$ slsart deploy`

## Drop resources from AWS
1. `$ slsart remove`