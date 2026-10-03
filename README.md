## Hi, I'm Chaithanya Reddy👋

**Cloud DevOps Engineer** building and automating cloud platforms on **AWS** and **Azure**, from infrastructure-as-code to Kubernetes to ML inference. I've worked in banking (Wells Fargo), healthcare (Centene) and IT services (TCS).

🟢 Open to full-time and contract Cloud / DevOps / Platform Engineering roles in the US.

### 📌 Featured projects

**🛒 [ShopFlow: Microservices on Kubernetes with CI/CD + GitOps](https://github.com/chaithanyareddyk3273/shopflow-app)** · [gitops repo](https://github.com/chaithanyareddyk3273/shopflow-gitops)
Three Python microservices (FastAPI, Postgres, RabbitMQ) on Kubernetes with Helm, built in three phases:
- **CI/CD + GitOps:** GitHub Actions tests, builds and **scans images with Trivy** (HIGH/CRITICAL fails the build), then commits the new image tag to a GitOps repo; **ArgoCD** deploys dev automatically and **prod is promoted by pull request** (rollback = `git revert`).
- **Production features:** **Prometheus + Grafana** with alert rules, **HPA autoscaling**, default-deny **NetworkPolicies**, **Sealed Secrets** (passwords encrypted in Git, rotated with no data loss), and **Argo Rollouts canary releases** that check the new version's success rate in Prometheus and **roll back automatically** (a version failing 50% of orders was aborted in 78 s).
- **AWS as code:** Terraform for VPC + EKS (Pod Identity, encrypted volumes, budget alert), validated and Trivy-scanned in CI.
- **Real bug write-ups:** events silently dropped at startup (fixed with RabbitMQ publisher confirms), and replicas racing on schema creation (fixed with a Postgres advisory lock).

**🔐 [Serverless Security Threat Detection Platform](https://github.com/chaithanyareddyk3273/aws-serverless-security-threat-detection)**
API Gateway → Lambda → S3 / SNS / CloudWatch with an ML classifier, provisioned with Terraform and checked by a GitHub Actions pipeline (lint, tests, Terraform validate, Checkov).

### 🧰 Toolbox

| Area | Tools |
|---|---|
| Cloud | AWS (EC2, Lambda, EKS, ECS, S3, DynamoDB, Kinesis, SageMaker) · Azure (VMs, App Service, AKS, Azure SQL) |
| IaC | Terraform · CloudFormation · ARM templates |
| Containers | Kubernetes (EKS / AKS) · Docker · Helm |
| CI/CD & GitOps | GitHub Actions · ArgoCD · Argo Rollouts · Jenkins · Azure DevOps Pipelines |
| Observability | Prometheus · Grafana · Alertmanager · CloudWatch · Azure Monitor · Log Analytics |
| Security | Trivy · Checkov · Sealed Secrets · NetworkPolicies · IAM / RBAC · Azure Key Vault · encryption at rest |
| Scripting | Python · Bash · PowerShell |

### 🏅 Certifications

- AWS Certified DevOps Engineer – Professional
- Certified Kubernetes Administrator (CKA)
- AWS Certified AI Practitioner
- AWS Certified Cloud Practitioner

### 📫 Connect

[LinkedIn](https://www.linkedin.com/in/chaithanya-reddy-26355428c/)
