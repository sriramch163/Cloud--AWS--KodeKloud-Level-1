# Define VPC CIDR

## 🎯 Objective of the Task

The objective of this task is to create a new Amazon VPC named `xfusion-vpc` in the `us-east-1` (N. Virginia) region.
The VPC must use the specified IPv4 CIDR block: `192.168.0.0/24`.

This VPC forms part of the Nautilus DevOps team's staged migration strategy, where different services will be deployed under isolated VPC environments to enhance network segmentation, operational flexibility, and security.

You must ensure:

- The VPC name is `xfusion-vpc`.
- The region is strictly `us-east-1`.
- The IPv4 CIDR block is `192.168.0.0/24`.
- The VPC creation is verified in the AWS console before task submission.

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
Define VPC CIDR/
├── Steps/
│   ├── cidr val.png
│   └── vpc name.png
├── Task/
│   └── task.png
├── steps.txt
└── Verify.png
```