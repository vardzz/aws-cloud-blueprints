# AWS Cloud Infrastructure Blueprints ☁️

A centralized library of Infrastructure as Code (IaC) templates engineered to automate cloud resource provisioning on Amazon Web Services (AWS) using AWS CloudFormation (YAML).

## 📁 Repository Structure

- `amazon-lex/`
  - `chatbot-template.yaml`: A production-ready Amazon Lex blueprint for a multi-intent conversational assistant with IAM execution policies.
- `aws-lambda-ses/`
  - `contact-form-pipeline.yaml`: A serverless contact form pipeline using Lambda, DynamoDB rate limiting, and SES email delivery.
- `aws-s3-static/`
  - `static-hosting-template.yaml`: A native S3 static website hosting blueprint with bucket policy and website configuration.

## 🚀 How to Deploy Templates

1. Log into your **AWS Management Console**.
2. Navigate to **AWS CloudFormation**.
3. Click **Create stack** (with new resources).
4. Select **Upload a template file** and choose the targeted `.yaml` blueprint file from this repository.
5. Execute the pipeline to automatically provision the serverless infrastructure in seconds.
