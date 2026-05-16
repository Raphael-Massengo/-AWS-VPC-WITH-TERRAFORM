# aws-vpc-terraform-project

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

## 📊 Architecture Diagram

<img width="848" height="342" alt="architecture drawio" src="https://github.com/user-attachments/assets/80a602c5-bb66-42dd-9efc-d4ab386ca289" />

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

## 📸 Screenshots

<img width="1920" height="1080" alt="Screenshot 2026-05-16 103009" src="https://github.com/user-attachments/assets/66d80fa6-cf39-4399-b4f9-a51d989b8f2a" />
<img width="1920" height="1080" alt="Screenshot 2026-05-16 103035" src="https://github.com/user-attachments/assets/d56942a3-1369-4b52-b532-88e36851a6b4" />
<img width="1920" height="1080" alt="Screenshot 2026-05-16 103059" src="https://github.com/user-attachments/assets/4789f880-7959-47a3-ba87-8f2a63aded4a" />
<img width="1920" height="1080" alt="Screenshot 2026-05-16 103149" src="https://github.com/user-attachments/assets/911e656c-0fa4-4d24-8209-f196ac1941b7" />
<img width="1920" height="1080" alt="Screenshot 2026-05-16 103245" src="https://github.com/user-attachments/assets/23e19d35-9d4a-4316-a02c-790b45efb8e9" />
<img width="1920" height="1080" alt="Screenshot 2026-05-16 103344" src="https://github.com/user-attachments/assets/e7b3aef3-8eb0-4b81-af05-e8e81b74af51" />
<img width="1920" height="1080" alt="Screenshot 2026-05-16 103431" src="https://github.com/user-attachments/assets/12e89588-6c65-43bf-ba29-d5eb2df6adf5" />
<img width="1920" height="1080" alt="Screenshot 2026-05-16 103515" src="https://github.com/user-attachments/assets/4adbcb1e-3df4-4de9-8737-dd5141f62e86" />
<img width="1920" height="1080" alt="Screenshot 2026-05-16 103533" src="https://github.com/user-attachments/assets/3c4bf025-1b46-4cf3-bd3c-d205a73f3d36" />
<img width="1920" height="1080" alt="Screenshot 2026-05-16 103554" src="https://github.com/user-attachments/assets/4bc95b88-a923-4d92-a475-b89fd3e6a7f9" />
<img width="1920" height="1080" alt="Screenshot 2026-05-16 103626" src="https://github.com/user-attachments/assets/6970ddde-739d-4b42-8b74-d1ce360090e2" />

---

## 🧠 Learning Outcomes

- AWS Infrastructure as Code
- Terraform resource management
- Cloud networking concepts
- Automated infrastructure deployment

---

# 👨‍💻 Author
Raphael Massengo
- CCNA Certified
- AWS Cloud Engineering Enthusiast
- Master’s Student in Data Analytics
