# AWS Certified Cloud Practitioner (CLF-C02)

This repository contains summarized notes and key concepts to prepare for the **AWS Certified Cloud Practitioner** exam. The goal is to provide a clear and structured overview of the topics covered in the certification.

---

## 📚 Index

1. [Introduction to Cloud Computing](#introduction-to-cloud-computing)
2. [Types of Cloud Computing](#types-of-cloud-computing)
3. [Cloud Pricing Fundamentals](#cloud-pricing-fundamentals)
4. [AWS Use Cases & Global Infrastructure](#aws-use-cases--global-infrastructure)
5. [Choosing an AWS Region](#choosing-an-aws-region)
6. [IAM - Identity and Access Management](#iam---identity-and-access-management)
7. [Accessing AWS](#accessing-aws)
8. [Amazon EC2 - Elastic Compute Cloud](#amazon-ec2---elastic-compute-cloud)
9. [EC2 Security](#ec2-security)
10. [EC2 Purchasing Options](#ec2-purchasing-options)

---

## ☁️ Introduction to Cloud Computing

**Traditional IT Components:**
- **Compute (CPU), Memory (RAM), Storage, Network, Database**
- Requires significant upfront investment and ongoing maintenance.

**Challenges:**
- Limited scalability
- High operational cost
- Delays in hardware provisioning
- Requires 24/7 support

**Cloud Computing Advantages:**
- **Flexibility**: Adapt resources as needed
- **Cost-effective**: Pay-as-you-go model
- **Scalability & Elasticity**
- **High Availability & Fault Tolerance**
- **Agility**: Faster development and deployment

---

## 🧱 Types of Cloud Computing

1. **IaaS** (Infrastructure as a Service): EC2, Azure VM, DigitalOcean
2. **PaaS** (Platform as a Service): AWS Elastic Beanstalk, Heroku
3. **SaaS** (Software as a Service): Gmail, Dropbox, Salesforce

---

## 💰 Cloud Pricing Fundamentals

- **Compute**: Charged per time used
- **Storage**: Pay for what you store
- **Data Transfer**:
  - **Inbound**: Free
  - **Outbound**: Charged

---

## 🌐 AWS Use Cases & Global Infrastructure

**Use Cases:**
- Web hosting
- Mobile and social apps
- Big Data
- Backup & storage
- Enterprise IT
- Gaming

**Infrastructure:**
- **Regions**: Clusters of data centers (e.g., `us-east-1`, `eu-west-3`)
- **Availability Zones (AZs)**: Independent failure domains
- **Edge Locations**: 400+ PoPs in 90+ cities for content delivery

---

## 📍 Choosing an AWS Region

Consider:
- Compliance & data governance
- Latency / proximity to users
- Service availability
- Pricing

---

## 🔐 IAM - Identity and Access Management

- **Users**, **Groups**, **Roles**, and **Policies**
- Apply **Least Privilege** principle
- **Password Policies** and **MFA** (Multi-Factor Authentication)
- **IAM Access Tools**:
  - Credential Reports
  - Access Advisor
- **Shared Responsibility Model**: AWS manages infrastructure security, customer manages identity and access

---

## 🔑 Accessing AWS

1. **Management Console** (UI)
2. **CLI** (Command Line Interface)
3. **SDKs** (Programming Language Integration)

**Access Keys**: Secure and private — never share them.

---

## 💻 Amazon EC2 - Elastic Compute Cloud

**Key Concepts:**
- Virtual machines in the cloud
- OS choices, CPU/RAM configs, storage types
- **EC2 User Data** for bootstrapping on launch

**Instance Types:**
- General Purpose
- Compute Optimized
- Memory Optimized
- Accelerated Computing
- Storage Optimized
- HPC Optimized

**Naming Convention**: e.g., `m5.2xlarge`

---

## 🔒 EC2 Security

- **Security Groups** (virtual firewalls)
  - Only allow rules
  - Control inbound/outbound traffic
  - Common ports: `22 (SSH)`, `80 (HTTP)`, `443 (HTTPS)`, etc.
- **Best Practice**: One group for SSH, others per app

---

## 🛒 EC2 Purchasing Options

| Option               | Description                                      |
|----------------------|--------------------------------------------------|
| **On-Demand**        | Pay-per-use, no commitment                       |
| **Reserved**         | 1 or 3-year contracts with discounts             |
| **Savings Plans**    | Commit to $/hour usage for better pricing        |
| **Spot Instances**   | Lowest cost, not guaranteed availability         |
| **Dedicated Hosts**  | Entire physical server reserved                  |
| **Capacity Reservation** | Reserve instance capacity in an AZ         |

> **Note**: AWS charges for all public IPv4 addresses. First 750 hours/month are free for the first 12 months under Free Tier.

---

## ✅ Exam Prep Tips

- Understand shared responsibility model
- Know differences between IaaS, PaaS, SaaS
- Be familiar with IAM concepts and best practices
- Review EC2 features, purchasing models, and security setup
- Understand AWS regions, AZs, and how to choose the right region

---

## 📎 References

- [AWS Training & Certification](https://aws.amazon.com/training/)
- [AWS CLI Setup](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
- [EC2 Instance Types](https://aws.amazon.com/ec2/instance-types/)

---

With Love Belén Corvalán Amil 🍀
