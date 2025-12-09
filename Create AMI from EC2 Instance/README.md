# Create AMI from EC2 Instance

## 🎯 Objective

As part of the migration strategy, the DevOps team needs to create a reusable machine image from an existing EC2 instance to support backup, scaling, and replication.

An EC2 instance named `nautilus-ec2` already exists in the `us-east-1` region.

The goal of this task is to:

Create an AMI from the EC2 instance `nautilus-ec2`, name the AMI `nautilus-ec2-ami`, and ensure the AMI reaches the `available` state.

This AMI will serve as a golden image for future deployments.

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
Create AMI from EC2 Instance/
├── Steps/
│   ├── ami creation.png
│   └── steps.txt
├── Task/
│   └── task.png
└── verify.png
```
