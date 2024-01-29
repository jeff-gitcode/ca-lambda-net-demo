

`````dotnetcli

# aws cli
https://aws.amazon.com/cli/


# lambda tools
$ dotnet tool install -g Amazon.Lambda.Tools


$ dotnet new --help

$ aws s3api list-buckets

$ dotnet new serverless.AspNetCoreWebAPI -n CALambdaNetDemo

$ dotnet add .\src\CALambdaNetDemo\ package  AWSSDK.Extensions.NETCore.Setup   
$ dotnet add .\src\CALambdaNetDemo\ package Amazon.Lambda.AspNetCoreServer  



$ dotnet lambda deploy-serverless --template serverless.template

# set aws profile
$ set AWS_PROFILE=localstack

# create bucket
$ aws cloudformation deploy --stack-name cfn-quickstart-stack --template-file "./cfn-quickstart-stack.yaml"
$ aws s3api create-bucket --bucket cloudformation-templates-2022

# pip
# install python

$ pip install awscli-local
```````