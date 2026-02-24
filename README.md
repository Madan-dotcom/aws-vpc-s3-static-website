# aws-vpc-s3-static-website
AWS project demonstrating VPC creation with public/private subnets and static website hosting using Amazon S3.
# AWS VPC & S3 Static Website Deployment

## 📌 Project Overview

This project demonstrates the implementation of core AWS networking and storage services. It includes the creation of a custom Virtual Private Cloud (VPC), configuration of public and private subnets across multiple Availability Zones, and deployment of a static website using Amazon S3.

The objective of this project was to strengthen foundational cloud networking concepts and understand resource configuration and lifecycle management in AWS.

---

## 🏗️ Task 1 – VPC Architecture Setup

### 🔹 VPC Configuration
- VPC CIDR: 10.0.0.0/16  
- Region: ap-south-1 (Mumbai)

### 🔹 Subnet Configuration
- Public Subnet: 10.0.1.0/24 (ap-south-1a)  
- Private Subnet: 10.0.2.0/24 (ap-south-1b)

### 🔹 Internet & Routing Configuration
- Internet Gateway attached to VPC
- Custom route table created for public subnet
- Route configured:
  - 0.0.0.0/0 → Internet Gateway
- Public subnet associated with custom route table
- Private subnet isolated with local routing only

---

## 🌐 Task 2 – Static Website Hosting Using Amazon S3

### 🔹 S3 Configuration
- Created S3 bucket
- Disabled Block Public Access (for static hosting)
- Enabled Static Website Hosting
- Configured index document: `index.html`
- Added bucket policy to allow public read access

### 🔹 Website Deployment
- Uploaded `index.html`
- Uploaded VPC architecture screenshot
- Verified public accessibility via S3 website endpoint

---

## 🖼️ Architecture Screenshot

<img width="1919" height="1026" alt="S3 Static Website Output" src="https://github.com/user-attachments/assets/b35ecc98-058f-45ff-b2b5-749748d0af96" />


---

## 🧠 Skills Demonstrated

- AWS VPC Configuration
- CIDR and Subnetting
- Route Table Creation & Association
- Internet Gateway Configuration
- Amazon S3 Static Website Hosting
- Cloud Networking Fundamentals
- Resource Lifecycle & Cost Management

---

## 📎 Project Status

Project successfully completed.  
All AWS resources were deleted after verification to prevent unnecessary charges under the Free Tier.
