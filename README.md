
## Create cloudformation script from an existing codepipeline
cloudformation stack cli usage: aws cloudformation create-stack --stack-name "CPRPM" --template-body file://cp-cf.json --parameters ParameterKey="gitHubOauth",ParameterValue="***"
