# Terraform AWS S3 Bucket Module

This Terraform module creates an S3 bucket on AWS.

## Initial Setup
- Make sure to have Terraform installed by checking command `terraform`.
- Make sure to have AWS CLI installed and Set Up the User Access Key and Password by command `aws configure`
- Change AWS Region as per wish in file `main.tf` in line 2 eg:`region = "us-east-1"`

## Variable Inputs

- `bucket_name` (Required): The name of the S3 bucket.
- `bucket_acl` (Optional, Default: "true"): The access control list (ACL) for the bucket : block_public_acls, block_public_policy, ignore_public_acls, restrict_public_buckets