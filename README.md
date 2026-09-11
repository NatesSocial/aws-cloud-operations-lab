# aws-cloud-operations-lab

# Secure AWS Cloud Operations Lab

This project demonstrates the deployment, administration, security,
monitoring, troubleshooting, and automation of a Linux web server in AWS.

## Technologies

AWS EC2, VPC, IAM, S3, CloudWatch, Linux, Bash, Git, GitHub, and Terraform.

## Project Objectives

- Configure a custom AWS network
- Deploy and administer a Linux server
- Apply least-privilege access controls
- Monitor system health and application logs
- Automate administrative checks
- Recreate the environment through infrastructure as code

## Network Security Decisions

- SSH is restricted to my current public IP to reduce unauthorized access.
- HTTP is publicly accessible because the server hosts a demonstration website.
- The server is deployed in a dedicated VPC and subnet.
- A custom route table explicitly controls internet routing.
