# Pull Request Template Guide

This folder contains multiple PR templates to standardize code reviews
across the organization. Select the **correct template** when opening a PR
based on the type of change.

---

## 📄 Available Templates

### 1. `feature.md`
Use this when:
- Adding new features
- Enhancing existing functionality
- Adding UI/API/database changes

---

### 2. `bug_fix.md`
Use this when:
- Fixing a user-reported or QA-found bug
- Correcting logic errors, crashes, or UI defects

---

### 3. `hotfix.md`
Use this for:
- Critical production fixes
- Emergency patches
- Security vulnerabilities

---

### 4. `documentation.md`
Use this when:
- Updating README, API docs, or onboarding guides
- Adding architectural notes or diagrams
- Improving inline documentation

---

## 🔒 Enforcement
Repositories may use branch protection + required checks to ensure:
- PR template is selected  
- PR description is complete  
- Linting/SAST/SCA scans pass  

---

## ❗ Notes for Developers
- Select the template that best matches the **primary purpose** of your PR.  
- Large PRs touching multiple areas should be broken into smaller PRs.  
- Maintain clarity and traceability by linking issues.  
- Follow the commit message template for consistent history.

---

For questions or improvements, contact the **DevOps / Platform Engineering Team**.
