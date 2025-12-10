# Implement VPC IPv6

## 🎯 Objective of the Task

The objective is to create a VPC named `xfusion-vpc` in the `us-east-1` region with:

- No manually entered IPv4 CIDR block (AWS will use the default 10.0.0.0/16 unless you specify otherwise)
- An Amazon-provided IPv6 CIDR block assigned to the VPC

This VPC will serve as part of the Nautilus DevOps team's staged AWS migration strategy, enabling IPv6-based workloads and future service deployments under a separate network boundary.

You must ensure:

- **VPC name:** xfusion-vpc
- **Region:** us-east-1
- **IPv6 assignment:** Amazon-provided IPv6 CIDR must be enabled
- **VPC is successfully created and visible in the console**

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
Implement VPC IPv6/
├── Steps/
│   ├── aws provider ipv6 cidr.png
│   ├── ipv4 cidr.png
│   └── vpc name.png
├── Task/
│   └── task.png
├── steps.txt
└── Verify.png
```