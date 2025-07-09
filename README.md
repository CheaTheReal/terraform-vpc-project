# Terraform VPC + EC2 Deployment Project

This project automates the creation of a secure AWS environment using **Terraform**. It includes a custom VPC, subnet, internet gateway, route table, security group, and an EC2 instance — all defined as code.

## 🚀 What This Project Builds

- ✅ Custom **VPC** with CIDR `10.0.0.0/16`
- ✅ **Public Subnet** and associated **Route Table**
- ✅ **Internet Gateway** for outbound internet access
- ✅ **Security Group** allowing SSH (22) and HTTP (80)
- ✅ **EC2 Instance** using Amazon Linux 2023
- ✅ Output of the EC2’s public IP after deployment

## 📂 Terraform File Structure

terraform-vpc-project/
├── main.tf # Resources (VPC, Subnet, EC2, SG, etc.)
├── variables.tf # Input variables
├── terraform.tfvars # Actual values (like key name, region)
├── outputs.tf # Shows EC2 public IP after apply
├── README.md # You're reading it!
