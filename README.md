## Hi, I'm Chaithanya 👋

**Cloud DevOps Engineer** building and automating cloud platforms on **AWS** and **Azure**, from infrastructure-as-code to Kubernetes to ML inference. I've worked in banking (Wells Fargo), healthcare (Centene) and IT services (TCS).

🟢 Open to full-time and contract Cloud / DevOps / Platform Engineering roles in the US.

### 📌 Featured projects

**🛒 [ShopFlow: Microservices on Kubernetes with CI/CD + GitOps](https://github.com/chaithanyareddyk3273/shopflow-app)** · [gitops repo](https://github.com/chaithanyareddyk3273/shopflow-gitops)
Three Python microservices (FastAPI, Postgres, RabbitMQ) deployed with Helm. GitHub Actions tests each service, builds the images, **scans them with Trivy** (HIGH/CRITICAL vulnerabilities fail the build) and pushes them to GHCR. CI then commits the new image tag to a GitOps repo, and **ArgoCD** deploys dev automatically. **Prod is promoted by pull request**, so every deployment is reviewed and rollback is `git revert`. Includes a real bug write-up: events silently dropped at startup, fixed with RabbitMQ publisher confirms.

**🔐 [Serverless Security Threat Detection Platform](https://github.com/chaithanyareddyk3273/aws-serverless-security-threat-detection)**
API Gateway → Lambda → S3 / SNS / CloudWatch with an ML classifier, provisioned with Terraform and checked by a GitHub Actions pipeline (lint, tests, Terraform validate, Checkov).

### 🧰 Toolbox

| Area | Tools |
|---|---|
| Cloud | AWS (EC2, Lambda, EKS, ECS, S3, DynamoDB, Kinesis, SageMaker) · Azure (VMs, App Service, AKS, Azure SQL) |
| IaC | Terraform · CloudFormation · ARM templates |
| Containers | Kubernetes (EKS / AKS) · Docker · Helm |
| CI/CD & GitOps | GitHub Actions · ArgoCD · Jenkins · Azure DevOps Pipelines |
| Observability | Prometheus metrics · CloudWatch · Azure Monitor · Log Analytics |
| Security | Trivy · Checkov · IAM / RBAC · Azure Key Vault · encryption at rest |
| Scripting | Python · Bash · PowerShell |

### 🏅 Certifications

- AWS Certified DevOps Engineer – Professional
- Certified Kubernetes Administrator (CKA)
- AWS Certified AI Practitioner
- AWS Certified Cloud Practitioner

### 📫 Connect

[LinkedIn](https://www.linkedin.com/in/chaithanya-reddy-26355428c/)
