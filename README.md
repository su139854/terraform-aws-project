# Terraform AWS Infrastructure Project

This project automates the creation of an AWS environment using Terraform.  
It includes a Virtual Private Cloud (VPC), subnet, route table, internet gateway, and an EC2 web server.

## 🧱 Architecture
- VPC with public subnet
- Internet Gateway and route table for outbound traffic
- Security group for HTTP, HTTPS, and SSH access
- Elastic IP attached to the EC2 instance
- Apache web server provisioned via user data

## ⚙️ Tools Used
- Terraform
- AWS (EC2, VPC, IGW, EIP)
- GitHub for version control

## 🚀 How to Deploy
1. Configure your AWS credentials  
   `aws configure --profile admin`
2. Initialize Terraform  
   `terraform init`
3. Review the plan  
   `terraform plan`
4. Apply changes  
   `terraform apply`
5. Access the web server using the public IP output.

## 🧠 Skills Demonstrated
- Infrastructure as Code (IaC)
- AWS networking and compute
- Security group and access control management
- GitHub workflow for cloud projects
