# CI/CD-infrastructure
Design provisioning and deployment of a docker based web app in a cloud.

## Tools used
- github
- jenkins
- ansible 
- docker  
- Terraform 
-------

### we want to create Infra
---------
- a Docker repository to push images to
- an ec2 instance that can pull and run those Docker images
- a database for the ec2/containers to connect to
- AWS access tokens and region set in the environment as $env:AWS_ACCESS_KEY_ID, $env:AWS_SECRET_ACCESS_KEY and §env:AWS_DEFAULT_REGION

### AWS services used
-----------
- EC2
- VPC
- ECR
- IAM
- RDS
