# Create Snapshot of RDS Instance

## 🎯 Objective of the Task

The objective of this task is to ensure proper database backup and disaster-recovery readiness by creating a manual snapshot of an existing RDS instance.

You must:

- Locate the running RDS instance named `devops-rds` in the `us-east-1` region.
- Create a manual snapshot of this instance.
- Name the snapshot exactly: `devops-rds-snapshot`.
- Ensure the snapshot appears in the RDS Snapshots list and its status becomes `available`.

This validates that the backup process is working and the team can restore the database if required.

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
Create Snapshot of RDS Instance/
├── Steps/
│   └── snapshot.png
├── Task/
│   └── task.png
├── steps.txt
└── Verify.png
```