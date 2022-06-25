# aws-cloud-formation-demo
Creating a VPC Infrastructure with AWS Cloud Formation

## Pre-requisite
- This project assume your have already setup you aws CLI.
You can use this resource to [setup your AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html)

## Nice to have
- Familiarity with basic Linux commands
- YAML Syntax
- JSON Syntax
- Basic understanding of Cloud Network

### Make your script executable: 
` chmod +x create-stack.sh update-stack.sh `

### Creating the VPC with a script
` ./create-stack.sh ourinfra.yml ourinfra.json `

### Updating the VPC with a script
`./update-stack.sh ourinfra.yml ourinfra.json`
