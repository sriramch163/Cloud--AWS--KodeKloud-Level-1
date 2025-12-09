# Change EC2 Instance Type

## 🎯 Objective of the Task

During migration, the Nautilus DevOps team found that EC2 instance `nautilus-ec2` is underutilized.
So the goal is:

✅ 1. Change EC2 instance type from `t2.micro` to `t2.nano`

This must be done only after status checks are completed (not in Initializing state).

✅ 2. Ensure the EC2 instance `nautilus-ec2` is in running state

after modifying the instance type.

📌 Region must be `us-east-1`.

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
Change EC2 Instance Type/
├── Steps/
│   ├── inst type.png
│   ├── t2.micro.png
│   └── verify.png
├── Task/
│   └── task.png
└── README.md
```
