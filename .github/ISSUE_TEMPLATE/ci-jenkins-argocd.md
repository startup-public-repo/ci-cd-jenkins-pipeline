---
name: "Jenkins to ArgoCD Integration Issue"
about: "Request assistance with linking a Jenkins pipeline to an ArgoCD GitOps deployment."
title: "[Jenkins ↔️ ArgoCD] Link Pipeline to GitOps Deployment"
labels: ["CI/CD", "Jenkins", "ArgoCD", "GitOps"]
assignees: [manupanand]
---

## Description

**As a** DevOps engineer  
**I want to** link a Jenkins job to trigger ArgoCD GitOps deployments  
**So that I can** automate application delivery through GitOps best practices.

## Requirements

1. **Jenkins Job Details**:
   - **Job Name**: [e.g., build-deploy-service-a]
   - **Pipeline Type**: Freestyle / Declarative / Scripted
   - **Trigger Action**:
     - Push Git commit with updated manifests
     - Call ArgoCD API webhook to sync
     - Other: [Specify]

2. **ArgoCD Application Details**:
   - **Application Name**: [e.g., service-a-app]
   - **GitOps Repository**: [e.g., https://github.com/startup-public-repo/repo]
   - **Target Branch**: [e.g., main or develop]

3. **Authentication/Access**:
   - **ArgoCD API Token**: Available / Needs creation
   - **Git Credentials**: Managed through Jenkins credential store (Y/N)

4. **Expected Behavior**:
   - Jenkins build success updates Git repo and triggers ArgoCD to deploy latest changes automatically.

5. **Optional Enhancements**:
   - Slack or email notifications post-deployment.
   - Add ArgoCD health checks after sync.

## Steps to Reproduce

1. Set up or modify Jenkins pipeline with GitOps repo update steps.
2. Configure ArgoCD webhook or ArgoCD CLI command from Jenkins.
3. Validate successful GitOps deployment through ArgoCD dashboard.

## Expected Outcome

Successful and automatic promotion of new changes to Kubernetes clusters via ArgoCD after Jenkins pipeline runs.

## Actual Outcome

_Describe any issues, errors, or missed steps if already attempted._

## Additional Context

- Logs/screenshots (if applicable):  
- Specific Jenkins plugins involved (if any):  
- Related pipeline IDs or URLs:  

## Checklist

Before submitting:
- [x] Jenkins job details are clear.
- [x] ArgoCD repo and app details are included.
- [x] Authentication methods are specified.

---

### Thank you for helping us automate GitOps better! 🚀
