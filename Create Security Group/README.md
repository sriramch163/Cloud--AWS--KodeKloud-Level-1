# Create Security Group

## 🎯 Objective of the Task

The objective is to create a Security Group in the default VPC in the `us-east-1` region for the Nautilus DevOps migration project.

This security group will allow:
- HTTP traffic (port 80) from anywhere (0.0.0.0/0)
- SSH traffic (port 22) from anywhere (0.0.0.0/0)

The security group must have:

| Setting | Value |
|---------|-------|
| Security Group Name | xfusion-sg |
| Description | Security group for Nautilus App Servers |
| Region | us-east-1 |
| Inbound Rule 1 | HTTP → Port 80 → CIDR 0.0.0.0/0 |
| Inbound Rule 2 | SSH → Port 22 → CIDR 0.0.0.0/0 |

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
Create Security Group/
├── Execution/
│   └── sg.png
├── Task/
│   ├── task - 1.1.png
│   └── task - 1.2.png
└── README.md
```
