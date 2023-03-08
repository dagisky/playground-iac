###  a high-availability web app using CloudFormation

## Deployment script

```aws cloudformation create-stack --stack-name infrastructure --template-body file://infrastructure.yml  --parameters file://infrastructure-parameters.json --region=us-east-1 --capabilities CAPABILITY_NAMED_IAM```

```aws cloudformation create-stack --stack-name serverInfrastructure --template-body file://servers.yml    --parameters file://server-parameters.json  --region=us-east-1```
