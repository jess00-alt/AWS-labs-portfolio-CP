# AWS-labs-portfolio-CP

Welcome to my AWS Cloud Practitioner hands-on lab portfolio. Each project below demonstrates my practical skills in configuring real AWS environments, managing infrastructure, and applying security best practices. These were completed through AWS Academy via ALX.

---

## 🧩 Lab 1: IAM Group Permissions & CloudTrail Activity Logs
**Date:** June 26, 2025  
**Region:** `us-east-1`

### 🎯 Objective
Simulate role-based access control in AWS by assigning users to IAM groups and validating actions using AWS CloudTrail logs.

### ✅ Key Tasks
- Assigned users to IAM groups: S3-Support, EC2-Support, EC2-Admin
- Verified user login activity and EC2 access using submission report

### 🖇️ Evidence
Submission Report ✅  
*All tasks validated with success: user assignments and activity traced in logs*

### 🛠️ Skills Used
`IAM policies` • `Group-based permissions` • `CloudTrail analysis` • `Access control`

---

## 🌐 Lab 2: VPC, Subnets & EC2 Web Deployment
**Date:** July 1, 2025  
**Region:** `us-east-1`

### 🎯 Objective
Set up a secure and scalable network using a VPC with public/private subnets and deploy a live-accessible EC2 instance.

### ✅ Key Tasks
- Created custom VPC with public and private subnets across AZs
- Configured route tables and associated them with correct subnets
- Deployed an EC2 web server accessible via public IP

### 🖇️ Evidence
Submission Report ✅  
*Instance `Web Server 1` launched successfully – website accessible at `http://52.87.207.198`*

### 🛠️ Skills Used
`VPC networking` • `Subnet CIDR planning` • `Route tables` • `Security groups` • `EC2 hosting`

---

## ⚙️ Lab 3: EC2 Lifecycle Management & Troubleshooting
**Date:** July 3, 2025  
**Region:** `us-east-1`

### 🎯 Objective
Manage EC2 instance lifecycle, modify configurations, retrieve logs, and handle stop protection issues.

### ✅ Key Tasks
- Launched EC2 instance `Web Server` with type `t2.small`
- Retrieved system logs via AWS Console
- Updated security group to allow TCP port 80
- Resized volume and disabled stop protection to stop instance

### 🖇️ Evidence
Submission Report ✅  
*Confirmed EC2 creation, system log retrieval, SG rule update, volume resize, and stop protection troubleshooting*

### 🛠️ Skills Used
`EC2 instance admin` • `Stop protection handling` • `EBS resizing` • `Security group updates` • `System logs`

---

## 💾 Lab 4: EBS Volume Management & Snapshot Recovery
**Date:** July 3, 2025  
**Region:** `us-east-1`

### 🎯 Objective
Demonstrate EBS volume operations including creation, attachment, mounting, snapshot backup, and restoration.

### ✅ Key Tasks
- Created 1GB volume `My Volume` and attached it to EC2 instance
- Mounted to `/mnt/data-store` and verified with `df -h`
- Created snapshot, restored volume, and confirmed it was mounted at `/mnt/data-store2`

### 🖇️ Evidence
Submission Report ✅  
*All volume, snapshot, and mount steps confirmed successfully*

### 🛠️ Skills Used
`EBS volume operations` • `Snapshot creation` • `Linux mounting` • `Disaster recovery` • `Storage lifecycle`

---

### 📌 Note:
These labs were completed using **AWS Academy** via the **ALX LMS**, so access to the AWS Console is restricted after lab completion. All evidence is based on detailed auto-generated submission reports that validated each task.

### ✨ Summary
These labs reflect my technical growth in AWS fundamentals — from IAM security to infrastructure deployment and storage recovery. I’m excited to bring these skills into real-world cloud projects and junior cloud roles.

> 💼 **Looking to connect or collaborate?** View more at [your-linkedin-or-personal-site-here] or contact me for project opportunities.
