# Launch EC2 Instance via AWS CLI

## 🎯 Objective of the Task

The objective of this task is to create and launch an EC2 instance using the AWS CLI (because the AWS Console access is restricted).

You must:

Create an EC2 instance using the default VPC in the `us-east-1` region.

Launch the instance with:

- **Instance name:** devops-ec2
- **AMI ID:** ami-0cd59ecaf368e5ccf
- **Instance type:** t2.micro
- **Key pair name:** devops-kp (RSA type)
- **Default security group** (already available by default)

Save the private key (devops-kp.pem) to your current working directory.

## 📚 About KodeKloud AWS Tasks

This task is part of the KodeKloud AWS hands-on learning series, designed to provide practical experience with AWS services. These tasks simulate real-world DevOps scenarios and help build proficiency in:

- AWS CLI operations
- EC2 instance management
- Security and access control
- Cloud infrastructure setup
- Best practices for AWS resource management

Each task includes step-by-step commands and verification screenshots to ensure successful completion.

## 📁 Directory Structure

```
Launch EC2 Instance via AWS CLI/
├── Commands/
│   ├── cmd - 1.1.png
│   └── cmd - 1.2.png
├── Task/
│   └── task.png
└── cmds.txt
```