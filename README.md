# Secure Private EC2 Hosting using Bastion Host & NAT Gateway

## 📌 Project Overview
This project demonstrates a secure AWS architecture where a private EC2 instance is accessed only through a Bastion Host and uses a NAT Gateway for outbound internet access.

The private EC2 hosts a static website cloned from GitHub and served using Apache.

---

## 🏗 Architecture
- Custom VPC
- Public Subnet (Bastion Host)
- Private Subnet (Web Server)
- NAT Gateway with Elastic IP
- Internet Gateway
- Route Tables
- Security Groups
- CloudFormation (IaC)

---

## 🔐 Security Design
- Private EC2 has **NO public IP**
- SSH access only via Bastion Host
- Internet access via NAT Gateway
- Least privilege security groups

---

## ⚙️ Tech Stack
- AWS EC2
- AWS VPC
- NAT Gateway
- CloudFormation
- Apache HTTP Server
- Git

---

## 🚀 Deployment Steps
1. Deploy CloudFormation stack
2. SSH into Bastion Host
3. Connect to Private EC2
4. Install Apache & Git
5. Clone GitHub website repo
6. Serve website using Apache

---

## 📸 Proof
Screenshots are available in the `screenshots/` folder showing:
- Stack creation
- Bastion login
- Private EC2 login
- Apache running
- Website output

---

## 💰 Cost Management
All AWS resources were deleted after testing to avoid charges.

---

## 👤 Author
**Thananjeyan (TJ)**  
Aspiring AWS DevOps Engineer
