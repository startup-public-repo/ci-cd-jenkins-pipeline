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
   - **GitOps Repository**: [e.g., https://github.com/org/service-a-gitops]
   - **Target Branch**: [e.g., main or develop]

3. **Authentication/Access**:
   - **ArgoCD API Token**: Available / Needs creation
   - **Git Credentials**: Managed through Jenkins credential store (Y/N)

4. **Expected Behavior**:
