
# Terraform – AWS S3 Bucket

This project provisions an **AWS S3 bucket** with the following configurations:

- Bucket name: `zohort-devops-ravindra`
- Versioning enabled
- Public access blocked
- Terraform state stored in an S3 backend with optional DynamoDB locking
- Outputs the bucket name after apply

---

## 📦 Prerequisites

- [Terraform](https://developer.hashicorp.com/terraform/downloads) >= 1.3.0
- AWS account with proper IAM permissions
- AWS CLI configured (`aws configure`)
- An **S3 bucket for Terraform backend** (e.g., `zohort-terraform-backend`)
- A **DynamoDB table** for state locking (e.g., `terraform-locks`)
