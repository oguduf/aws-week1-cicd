# GitHub to AWS CI/CD Pipeline

## Objective

Demonstrate a functional CI/CD connection between GitHub Actions and AWS.

## Pipeline

```text
GitHub
  ↓
Checkout
  ↓
Build 
  ↓
Test
  ↓
Security Scan
  ↓
Authenticate to AWS
  ↓
Publish deployment proof to Amazon S3
