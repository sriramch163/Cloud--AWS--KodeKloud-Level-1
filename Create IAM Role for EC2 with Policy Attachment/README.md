# Create IAM Role for EC2 with Policy Attachment

## 🎯 Objective

IAM roles allow AWS services to assume permissions to interact with other AWS resources securely. As part of IAM resource configuration, the DevOps team needs to create a service role for EC2 that uses an existing IAM policy.

The goal of this task is:

Create an IAM role named `iamrole_ravi`, choose AWS Service as the trusted entity type with use case EC2, and attach the IAM policy `iampolicy_ravi` to the role.

This role will allow EC2 instances to perform actions defined in the attached policy.

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
Create IAM Role for EC2 with Policy Attachment/
├── Steps/
│   ├── entity type.png
│   ├── name.png
│   ├── policy.png
│   ├── role name.png
│   └── steps.txt
├── Task/
│   └── task.png
└── Verify.png
```
