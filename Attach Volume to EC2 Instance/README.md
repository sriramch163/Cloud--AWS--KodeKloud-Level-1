# Attach Volume to EC2 Instance

## 🎯 Objective

As part of the migration project, an EC2 instance named `xfusion-ec2` and an EBS volume named `xfusion-volume` already exist in the `us-east-1` region.

The objective is to:

Attach the EBS volume `xfusion-volume` to the EC2 instance `xfusion-ec2` and set the device name to `/dev/sdb` during attachment.

This allows the instance to use additional storage for application data or logs.

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
Attach Volume to EC2 Instance/
├── Steps/
│   └── attach vol.png
├── Task/
│   └── task.png
├── steps.txt
└── verify.png
```
