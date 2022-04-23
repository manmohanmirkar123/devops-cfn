# devops-cfn

This Cfn is created to practice AWS Devops Professional exam


command for running cfn template

aws cloudformation create-stack --stack-name myEC2stack --template-body file://0-ec2.yaml

aws cloudformation update-stack --stack-name myEC2stack --template-body file://1-ec2.yaml --parameters ParameterKey=SecurityGroupDescription,ParameterValue=Greatsg

aws cloudformation delete-stack --stack-name myEC2stack