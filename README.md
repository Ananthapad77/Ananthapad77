<h1 align="center">Ananthapadmanabhan G</h1>
<h3 align="center">AWS Cloud & DevOps Engineer | SRE | 2+ Years in Production AWS</h3>

<p align="center">
  Terraform · Docker · Kubernetes · CI/CD · DevSecOps · AIOps
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ananthapadmanabhan-aws-devops/">LinkedIn</a> ·
  <a href="mailto:g.ananthapad7@gmail.com">Email</a>
</p>

---

## About

AWS Cloud & DevOps Engineer with **2+ years of experience** running production AWS environments at **Zeb** and **Avasoft**: monitoring critical systems, managing incidents, and keeping services highly available.

I combine that operations background with hands-on infrastructure automation: Infrastructure as Code, containers, Kubernetes, CI/CD, and security in the pipeline.

**Open to:** AWS Cloud Engineer · DevOps Engineer · SRE · Platform Engineer · Cloud Support Engineer roles

---

## Featured Projects

### 🥇 K8s-Sentry: AI-Assisted Incident Triage for Azure AKS
Read-only SRE agent that receives Azure Monitor alerts, collects pod events and logs through the Kubernetes API, masks secrets before sending evidence to an LLM, and posts a root-cause summary with safe remediation steps to Slack. Built with strict read-only RBAC, namespace scoping, and a heuristic fallback if the LLM is unavailable. AKS provisioned with Terraform, deployed with Helm, tested with pytest, CI via GitHub Actions.
**Stack:** Python · FastAPI · Azure AKS · Kubernetes API · Terraform · Helm · Docker · GitHub Actions
[Repo](https://github.com/Ananthapad77/k8s-sentry)

### AWS Three-Tier Infrastructure: Terraform, CloudFormation & Ansible
Highly available three-tier AWS deployment across 2 AZs: VPC, ALB, Auto Scaling web tier, Multi-AZ RDS, bastion host. Modular Terraform with dev/prod environments, CloudFormation-bootstrapped remote state, and Ansible for configuration.
**Stack:** Terraform · CloudFormation · Ansible · AWS
[IaC repo](https://github.com/Ananthapad77/aws-three-tier-iac) · [Application repo](https://github.com/Ananthapad77/aws-three-tier-web-architecture)

### CINDER: Dockerized App on AWS ECS Fargate
Highly available deployment: ALB in public subnets routing to ECS Fargate tasks in private subnets across 2 AZs, with custom VPC, security groups, CloudWatch/SNS alerting, AWS Config compliance rules and CloudTrail audit logging.
**Stack:** Docker · ECS Fargate · ALB · CloudWatch · AWS Config · CloudTrail
[Repo](https://github.com/Ananthapad77/Docker_ECS_Fargate)

### AWS Cost Optimization Automation
Serverless pipeline (EventBridge, Lambda, DynamoDB, SNS) that scans an AWS account daily for unattached EBS volumes, unused Elastic IPs and idle EC2 instances, and emails a report with estimated savings.
**Stack:** Python · Lambda · EventBridge · DynamoDB · SNS
[Repo](https://github.com/Ananthapad77/aws-cost-optimization-automation)

### GKE GitOps Platform *(team project)*
Terraform-provisioned GKE platform with ArgoCD continuously reconciling manifests from Git, NGINX Ingress with cert-manager TLS, Sealed Secrets, and Prometheus/Grafana/OpenTelemetry observability. My part: [your contribution].
**Stack:** Terraform · GKE · ArgoCD · Prometheus · Grafana
[Infra repo](https://github.com/Ananthapad77/gke-gitops-infra) · [App repo](https://github.com/Ananthapad77/gke-microservice-app)

### Zero-Trust DevSecOps Pipeline *(2-person project)*
CI/CD pipeline with Semgrep SAST, container and dependency scanning, and OPA policy-as-code gates, with Terraform-managed infrastructure. My part: [your contribution].
**Stack:** GitHub Actions · OPA · Semgrep · Terraform
[Repo](https://github.com/Ananthapad77/zt-devsecops-pipeline)

---

## Tech Stack

| Area | Tools |
|---|---|
| **Cloud** | AWS (VPC, EC2, ECS/Fargate, ALB, ECR, S3, CloudFront, RDS, ElastiCache, Lambda, DynamoDB, EventBridge, IAM, Secrets Manager, Config, CloudTrail), GCP (GKE), Azure (AKS, Azure Monitor) |
| **Infrastructure as Code** | Terraform, CloudFormation, Ansible |
| **Containers & Kubernetes** | Docker, Kubernetes, Helm, ArgoCD (GitOps), ECS/Fargate |
| **CI/CD & DevSecOps** | GitHub Actions, Jenkins, Semgrep, OPA (policy-as-code) |
| **Monitoring & Observability** | Datadog, CloudWatch, Prometheus, Grafana, OpenTelemetry, OpManager |
| **Languages** | Python, Bash, Node.js |
| **ITSM & Access** | Jira, ServiceNow, Okta (SSO) |
| **Version Control** | Git, GitHub |

---

## Currently Working On
- Extending my projects with GitOps and progressive delivery
- Preparing for AWS Solutions Architect Associate and CKA certifications

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Ananthapad77&show_icons=true&theme=default&hide_border=true" alt="GitHub Stats" height="165"/>
</p>
