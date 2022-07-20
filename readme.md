to deploy run the command

aws cloudformation create-stack --stack-name <name> --template-body file://./ecs.yml --capabilities CAPABILITY_NAMED_IAM
 -- parameters 'ParameterKey=<key>,ParameterValue=<Value> '