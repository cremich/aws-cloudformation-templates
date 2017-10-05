# AWS Cloudformation templates
A collection of useful cloudformation templates. Feel free to use, fork or give me some feedback.

## Usage
Simply create a stack via AWS Console or via the AWS cli tool:
```bash
aws cloudformation create-stack \
    --stack-name my-very-first-cloudformation-stack \
    --template-body file://path/to/my/template.yml \
    --parameters \
        ParameterKey=my-parameter,ParameterValue=my-value\
    --capabilities CAPABILITY_IAM
```

For more information about the cloudformation cli, see the [aws cli command reference](http://docs.aws.amazon.com/cli/latest/reference/cloudformation/).

## Found a bug?
Please give us some information about errors or bugs and create an [issue](https://github.com/cremich/aws-cloudformation-templates/issues)  

## About
An [onkelpixel](http://www.onkelpixel.de) project.
