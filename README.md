# serverless-aws-codepipeline-ci-cd-example

Sample project for demonstrating CI/CD of a serverless application with the Serverless Framework and AWS CodePipeline.

A full setup requires AWS CodePipeline and AWS CodeBuild to be configured.

## Geting started

```
# Install dependencies
npm install

# Deploy the stack
npm run sls -- deploy

# Invoke endpoint
curl -i https://xyz.execute-api.us-east-1.amazonaws.com/
```

## References

- https://epsagon.com/tools/aws-ci-cd-pipeline-tools/
- https://medium.com/quantica/setup-ci-cd-pipeline-with-aws-lambda-and-serverless-framework-f624773f355e (part 1 of series)
- https://medium.com/quantica/setup-ci-cd-pipeline-with-aws-lambda-and-the-serverless-framework-313a5d3b6001 (part 2 of series)
