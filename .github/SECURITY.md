# Security Policy

We take the security of our systems and data seriously. This document describes how to report vulnerabilities and our general security posture.

---

## 🔐 Reporting a Vulnerability

If you believe you have found a security vulnerability, please **do not**
open a public GitHub issue.

Instead, contact us via:

- Email: security@decipherheathcare.com

Please include:

- A detailed description of the issue
- Steps to reproduce
- Affected repository / service / environment
- Any logs or screenshots that help illustrate the problem

We request you:

- Do not attempt to access data that does not belong to you
- Do not perform actions that could impact availability or integrity
- Follow responsible disclosure practices

---

## Severity

Severity categories:

- **Critical** – remote code execution, auth bypass, data exfiltration  
- **High** – privilege escalation, sensitive data exposure  
- **Medium** – security misconfigurations, missing hardening  
- **Low** – informational, best practices, non-exploitable issues  

---

## 🔒 Security Expectations for Contributors

All contributors are expected to:

- Avoid hard-coding credentials, tokens, or secrets
- Use the approved secrets management solution (e.g., AWS Secrets Manager / Azure Key Vault)
- Follow least-privilege principles for IAM roles and access policies
- Ensure new endpoints include authentication, authorization, and logging
- Avoid introducing dependencies with known high/critical CVEs

Security checks may include:

- SAST (e.g., CodeQL)
- SCA / dependency scanning
- Container image scanning
- IaC security scanning (Terraform, Kubernetes, etc.)

---

## 📚 Related Policies (Internal)

- Secure Coding Guidelines
- Cloud Security Baseline (AWS / Azure)
- Vulnerability Management Procedure
- Encryption & Key Management Policy
