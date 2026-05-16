# Terraform AWS VPC Project

## 🚀 Overview

This project demonstrates Infrastructure as Code (IaC) using Terraform to automate AWS cloud infrastructure deployment.

The infrastructure includes:
- Custom VPC
- Public subnet
- Internet Gateway
- Route Tables
- Security Groups
- EC2 Web Server

---

## ⚙️ Technologies Used

- Terraform
- AWS EC2
- AWS VPC
- AWS Security Groups

---

## 🧱 Infrastructure Created

- VPC (`10.0.0.0/16`)
- Public Subnet (`10.0.1.0/24`)
- Internet Gateway
- Route Table Association
- EC2 Instance with Apache Web Server

---

## 🚀 Deployment

Initialize Terraform:

```bash
terraform init
```

Preview infrastructure:

```bash
terraform plan
```

Deploy infrastructure:

```bash
terraform apply
```

Destroy infrastructure:

```bash
terraform destroy
```

---

## 🌐 Web Server Test

After deployment:

```text
http://EC2-PUBLIC-IP
```

---

## 🔐 Security Features

- Security Groups configured for HTTP and SSH
- Least privilege access principles
- Infrastructure managed as code

---

## 🧠 Learning Outcomes

- AWS Infrastructure as Code
- Terraform resource management
- Cloud networking concepts
- Automated infrastructure deployment

---

## 👨‍💻 Author

Raphael Massengo
