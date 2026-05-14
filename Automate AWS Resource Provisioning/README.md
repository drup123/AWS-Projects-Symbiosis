# 🚀 Automate AWS Resource Provisioning

![Python](https://img.shields.io/badge/Python-3.13-blue?style=for-the-badge&logo=python)
![Boto3](https://img.shields.io/badge/Boto3-AWS-orange?style=for-the-badge)
![AWS](https://img.shields.io/badge/AWS-Cloud-black?style=for-the-badge&logo=amazonaws)
![Automation](https://img.shields.io/badge/Automation-Project-green?style=for-the-badge)

This project demonstrates how to automate AWS resource provisioning using **Python** and **Boto3 (AWS SDK for Python)**.

The script automates the creation and management of AWS resources such as:

- Amazon S3 Bucket
- IAM User
- EC2 Instance
- Security Group usage

---

# 📌 Project Overview

Manual provisioning of AWS resources can be time-consuming and repetitive.  
This project automates the process using Python scripts and AWS SDK.

## ✅ Features

- Create an S3 Bucket automatically
- Create IAM Users using Python
- Attach existing Security Groups
- Launch EC2 instances
- Error handling and logging
- Infrastructure automation using Boto3

---

# 🛠️ Technologies Used

- Python 3.13
- Boto3 (AWS SDK for Python)
- AWS IAM
- AWS EC2
- AWS S3
- VS Code

---

# 📂 Project Structure

```bash
Automate-AWS-Resource-Provisioning/
│
├── provision.py
├── requirements.txt
├── README.md
└── screenshots/
```

---

# ⚙️ Setup Instructions

## 1️⃣ Install Dependencies

```bash
pip install boto3
```

---

## 2️⃣ Configure AWS Credentials

```bash
aws configure
```

Enter:

- AWS Access Key
- AWS Secret Key
- Region
- Output format

---

## 3️⃣ Run the Script

```bash
python provision.py
```

---

# 🖥️ Screenshots

---

## 1️⃣ Script Execution in VS Code Terminal

![Terminal Output](./screenshots/terminaloutput.png)

### 📖 Description

This screenshot shows the successful execution of the Python automation script.

### ✅ Operations Performed

- S3 Bucket created successfully
- IAM User created successfully
- Existing Security Group attached
- EC2 provisioning attempted
- Script execution completed

### ⚠️ Note

An EC2 error occurred due to an invalid AMI ID:

```bash
InvalidAMIID.Malformed
```

This can be fixed by replacing the AMI ID with a valid one for the selected AWS region.

---

## 2️⃣ S3 Bucket Created Successfully

![S3 Bucket](./screenshots/s3bucket_creation.png)

### 📖 Description

This screenshot shows the Amazon S3 bucket created automatically by the Python script.

### ✅ Bucket Details

- Bucket Name: `my-unique-bucket-12345-demo123`
- Status: Successfully Created
- Storage Type: Amazon S3
- Region: AWS Cloud

The bucket is currently empty and ready for object uploads.

---

## 3️⃣ IAM Users Created

![IAM Users](./screenshots/Iam_User_creation.png)

### 📖 Description

This screenshot displays the IAM users available in the AWS account.

### ✅ Users

- `demo-user-boto325` → Created using the automation script
- `drup-patil@2652004` → Existing AWS IAM user

These users can be used for secure AWS access and permission management.

---

# 💡 Learning Outcomes

Through this project, I learned:

- AWS resource automation
- Working with Boto3 SDK
- IAM user management
- S3 bucket creation
- EC2 provisioning
- AWS authentication and permissions
- Infrastructure scripting using Python

---

# 🚀 Future Improvements

- Add VPC automation
- Automate Security Group creation
- Launch fully configured EC2 instances
- Add CloudWatch monitoring
- Convert project into Infrastructure as Code (IaC)

---

# 👨‍💻 Author

## Drup Patil

AWS | Python | Cloud Automation | DevOps Enthusiast

---
