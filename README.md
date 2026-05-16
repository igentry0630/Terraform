# Automated AWS Infrastructure Deployment via Terraform

A production-grade infrastructure blueprint deploying a highly available AWS cloud architecture using Terraform (Infrastructure as Code).

## 🛠️ Architecture Components
- **Networking:** Custom VPC with public and private subnets across multiple Availability Zones.
- **Compute:** Scalable EC2 instances configured via security groups for restricted access.
- **Storage:** Secure Amazon S3 buckets utilizing encryption-at-rest for artifact management.
- **Identity & Access:** IAM roles and policies enforcing the principle of least privilege.

## 🚀 How to Deploy
1. Ensure your AWS CLI credentials are configured locally.
2. Initialize the working directory and download providers:
   `terraform init`
3. Review the execution plan to verify resources:
   `terraform plan`
4. Apply the configuration to deploy infrastructure:
   `terraform apply`

## 📊 Key Highlights
- **No Configuration Drift:** Enforces state management principles to ensure repeatable environment builds.
- **Modularity:** Leveraged structured variables (`variables.tf`) and outputs (`outputs.tf`) to maximize code reusability.
