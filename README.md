# aws-vpc-s3-static-website
AWS project demonstrating VPC creation with public/private subnets and static website hosting using Amazon S3.
# AWS VPC and S3 Static Website Project

## 📌 Project Overview
This project demonstrates:

- Creation of a custom VPC
- Configuration of Public and Private Subnets in different Availability Zones
- Internet Gateway attachment
- Route table configuration
- Deployment of a Static Website using Amazon S3

---

## 🏗️ Task 1 – VPC Setup

- VPC CIDR: 10.0.0.0/16
- Public Subnet: 10.0.1.0/24 (ap-south-1a)
- Private Subnet: 10.0.2.0/24 (ap-south-1b)
- Internet Gateway attached
- Public route table configured with:
  0.0.0.0/0 → Internet Gateway

---

## 🌐 Task 2 – Static Website Hosting

- Created S3 bucket
- Disabled Block Public Access
- Enabled Static Website Hosting
- Uploaded index.html and architecture screenshot
- Added bucket policy for public access

---

## 🖼️ Architecture Screenshot

![VPC Architecture](vpc-task-one.png)

---

## 🔗 Live Website URL

http://aws-s3-task-two.s3-website.ap-south-1.amazonaws.com

---

## 🧠 Skills Demonstrated

- AWS VPC
- Subnetting & CIDR
- Route Tables
- Internet Gateway
- Amazon S3
- Static Website Hosting
- Cloud Networking Fundamentals
