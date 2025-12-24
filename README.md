# Cloud Resume Project

## Overview
This project demonstrates core cloud engineering fundamentals by deploying a static resume website using modern cloud services, Infrastructure as Code, and CI/CD.

The goal is to build, deploy, and operate a small but production-style cloud workload end-to-end.

## Architecture
**(Diagram coming soon)**

Planned components:
- Static website hosting (cloud object storage)
- CDN for global delivery
- DNS + HTTPS
- CI/CD: GitHub Actions (automated deploy to Azure Storage Static Website)
- Frontend: HTML / CSS
- Version Control: Git + GitHub

## Deployment 
This project is deployeed automatically via CI/CD using GitHub Actions.

Steps (high level):
1. Code pushed to 'main' branch
2. GitHub Actions workflow is triggered
3. The pipeline authenticates to Azure using a Service Principal (RBAC)
4. Static site files are uploaded to the Azure Storage '$web' container
5. The website is updated without manual intervention

## What I'm Practicing
- Cloud fundamentals (networking, storage, IAM)
- Infrastructure as Code workflows
- CI/CD automation
- Reading logs and troubleshooting failed deployments
- Writing clear technical documentation

## Status
In progress - actively building

## Next Steps
- ✅ Deploy initial static site
- ✅ Add CI/CD pipeline
- Implemnt IaC
- Add monitoring
- Document lessons learned
