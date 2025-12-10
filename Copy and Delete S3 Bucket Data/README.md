# Copy and Delete S3 Bucket Data

## 🎯 Objective of the Task

The objective of this task is to clean up unused AWS resources created during previous migration activities. Specifically:

Copy all objects from the existing S3 bucket `xfusion-bck-29070` to the `/opt` directory on the aws-client host.

Delete the S3 bucket `xfusion-bck-29070` after confirming the files have been copied locally.

Ensure all operations are performed in the `us-east-1` region.

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
Copy and Delete S3 Bucket Data/
├── Commands/
│   └── cmd.png
├── Task/
│   └── task.png
├── cmds.txt
└── Verify.png
```