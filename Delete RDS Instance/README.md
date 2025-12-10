# Delete RDS Instance

## 🎯 Objective of the Task

The objective of this task is to delete the Amazon RDS instance named `devops-rds` that is running in the `us-east-1` (N. Virginia) region.

This cleanup activity is part of a migration effort where temporary resources created earlier must be removed to reduce cost, avoid unused infrastructure, and maintain an optimized AWS environment.

Before submitting the task, you must ensure that:

- The RDS instance `devops-rds` is fully deleted.
- No snapshots or automated backups are blocking the deletion.
- The deletion is performed only in the `us-east-1` region.

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
Delete RDS Instance/
├── Steps/
│   └── deleting db.png
├── Task/
│   └── task.png
├── steps.txt
└── verify.png
```