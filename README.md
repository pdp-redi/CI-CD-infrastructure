# CI-CD-infrastructure
Design provisioning and deployment of a docker based web app in a cloud.

## CI/CD - tools
- github
- jenkins
- ansible
- docker

## Design Provisioning and Deployment - tool
- Terraform
-------

creating Iac
---------
- a Docker repository to push images to
- an ec2 instance that can pull and run those Docker images
- a database for the ec2/containers to connect to

AWS services used
----------
- EC2
- VPC
- ECR
- IAM
- RDS
