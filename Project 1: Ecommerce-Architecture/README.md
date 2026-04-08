# 🛒 Scalable E-Commerce Architecture on AWS

## 📌 Overview

Implemented a highly available and scalable 3-tier architecture to handle high traffic workloads.

## 🏗️ Services Used

* EC2 (Application Layer)
* Application Load Balancer
* Auto Scaling Group
* RDS (Multi-AZ)
* S3 + CloudFront
* VPC (Public & Private Subnets)

## 🚀 Key Features

* High availability across multiple AZs
* Fault tolerance with Auto Scaling
* Secure backend in private subnet
* Optimized content delivery with CloudFront

## ⚙️ Implementation Steps

1. Created VPC with public & private subnets
2. Deployed EC2 instances in private subnet
3. Configured ALB for traffic routing
4. Enabled Auto Scaling
5. Setup RDS (Multi-AZ)
6. Integrated S3 + CloudFront

## 🎯 Outcome

Designed a production-ready scalable system capable of handling traffic spikes efficiently.
