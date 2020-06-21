# Ejemplo demo para crear una instancia con Ansible desde AWS CloudFormation
Demo de ejemplo para crear una instancia con Ansible desde CloudFormation AWS
Adaptado de: https://aws.amazon.com/es/blogs/infrastructure-and-automation/automate-ansible-playbook-deployment-amazon-ec2-github/

# Ejecutar desde AWS Cli
aws cloudformation create-stack --stack-name demo --template-body file://demo-cloudformation.yaml --parameters file://parameters.json