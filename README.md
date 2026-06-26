# CGE Portfolio – Compliant S3 Terraform Module (Lab 2‑3)

# Compliant S3 Bucket Module

This Terraform module provisions a fully compliant Amazon S3 bucket that enforces the following NIST 800‑53 controls:

- **SC‑28** – Encryption at rest using AES‑256
- **AU‑3 / AU‑6** – Audit logging to a dedicated log bucket
- **CM‑6** – Mandatory tagging for configuration management
- **AC‑3** – Public access restrictions (all four block settings enabled)

The module outputs the bucket name, bucket ARN, encryption algorithm, and log bucket ARN. Machine‑readable evidence for this module is located in `evidence/lab-2-3/`.


This repository contains my work for the Convergent Governance Engineering (CGE) labs, beginning with a fully compliant AWS S3 bucket module built in Terraform. The module enforces multiple NIST 800‑53 controls through infrastructure-as-code and produces machine‑readable evidence for verification.

## 🔒 Controls Implemented
- **SC‑28** – Encryption at Rest (AES‑256)
- **AU‑3 / AU‑6** – Audit Logging to a dedicated log bucket
- **CM‑6** – Mandatory tagging for configuration management
- **AC‑3** – Public access restrictions (all four block settings enabled)

## 📁 Repository Structure

## 🧪 Evidence
All compliance evidence is generated using:

These JSON files provide machine‑readable proof of encryption, logging, versioning, tagging, and access‑block configuration.

## 🚀 How to Use

## 🧹 Cleanup
To avoid AWS charges:
