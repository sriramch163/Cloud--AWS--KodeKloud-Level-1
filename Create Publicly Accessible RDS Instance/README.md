# Create Publicly Accessible RDS Instance

## 🎯 Objective of the Task

The objective of this task is to create a MySQL RDS database instance on AWS as part of the migration preparation for the Nautilus DevOps team. The database must be publicly accessible and created using free-tier compatible settings.

You must configure the RDS instance exactly as specified below:

- **RDS Instance Name:** xfusion-rds
- **Engine:** MySQL v8.4.5
- **Instance Class:** db.t3.micro (free tier)
- **Master Username:** xfusion_admin
- **Storage Type:** gp2
- **Storage Size:** 5 GiB
- **Public Access:** Enabled

Keep all other settings default.

Ensure the instance reaches Available state before submitting.

This prepares a lightweight database environment required for the team's ongoing migration initiatives.

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
Create Publicly Accessible RDS Instance/
├── Steps/
│   ├── db-idntifier, db-admin, passwd.png
│   ├── engine version.png
│   ├── instance type.png
│   ├── pub access.png
│   ├── sql.png
│   ├── storage.png
│   └── template.png
├── Task/
│   └── task.png
├── steps.txt
└── Verify.png
```