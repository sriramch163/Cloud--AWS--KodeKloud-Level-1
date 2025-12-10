# Delete VPC

## 🎯 Objective of the Task

The objective is to delete the VPC named `datacenter-vpc` located in the `us-east-1` (N. Virginia) region.
This cleanup task supports the Nautilus DevOps team's phased AWS migration strategy by removing unused or obsolete network environments.

Before deleting the VPC, you must ensure:

- The correct VPC (`datacenter-vpc`) is selected.
- All dependent resources (subnets, route tables, internet gateways, NAT gateways, security groups, etc.) are removed because AWS will not allow deleting a VPC with attached components.
- The task is executed only in the `us-east-1` region.

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
Delete VPC/
├── Steps/
│   └── deleting vpc.png
├── Task/
│   └── task.png
├── steps.txt
└── Verify.png
```