<div align="center">

<h1>Harshit Kandhwey</h1>

<p><strong>Cloud & DevOps Engineer</strong> — AWS infrastructure · CI/CD pipelines · Enterprise migrations</p>

<a href="https://linkedin.com/in/harshitkandhwey">
  <img src="https://img.shields.io/badge/LinkedIn-harshitkandhwey-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
&nbsp;
<a href="mailto:harshitkandhwey@outlook.com">
  <img src="https://img.shields.io/badge/Email-harshitkandhwey@outlook.com-0078D4?style=flat-square&logo=microsoft-outlook&logoColor=white" alt="Email"/>
</a>
&nbsp;
<a href="./Harshit_Kandhwey_Resume.pdf">
  <img src="https://img.shields.io/badge/Resume-Download-00B050?style=flat-square&logo=adobeacrobatreader&logoColor=white" alt="Resume"/>
</a>
&nbsp;
<img src="https://komarev.com/ghpvc/?username=harshit-kandhwey&style=flat-square&color=brightgreen&label=Profile+Views" alt="Profile views"/>

</div>

---

2.5+ years designing AWS infrastructure and automating operations at **Trianz Digital Consulting** — delivering enterprise cloud migrations for **GE Healthcare, MUFG, and Telenor**.

---

## ⚡ Currently

- **At work:** Driving AWS cloud migration pipelines for enterprise clients across healthcare, finance, and telecom
- **Building:** Extending [Ephemeral Deploy](https://github.com/harshit-kandhwey/ephemeral-deploy) with EKS and Helm-based deployments
- **Exploring:** Kubernetes, ArgoCD, and GitOps patterns on top of the existing Terraform + ECS stack
- **Next cert:** AWS DevOps Engineer Professional

---

## 🛠️ Tech Stack

**Cloud**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=FF9900)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazon-ec2&logoColor=white)
![ECS](https://img.shields.io/badge/ECS_Fargate-FF9900?style=flat-square&logo=amazon-ecs&logoColor=white)
![RDS](https://img.shields.io/badge/RDS-527FFF?style=flat-square&logo=amazon-rds&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazon-s3&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=aws-lambda&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square&logo=amazon-cloudwatch&logoColor=white)

**IaC & CI/CD**

![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=flat-square&logo=terraform&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-FF4F8B?style=flat-square&logo=amazon-aws&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)

**Containers & Observability**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**Scripting & OS**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🚀 Featured Projects

### [Ephemeral Deploy — Production AWS/ECS DevOps Pipeline](https://github.com/harshit-kandhwey/ephemeral-deploy)

> Production-grade containerized REST API deployment on AWS with full observability and keyless CI/CD

- Modular Terraform across **8 modules** (VPC, ECS, RDS, ElastiCache, ECR, IAM, security groups, monitoring) with S3 remote state and per-env isolation
- **OIDC-based CI/CD** — zero stored credentials; Terraform-native blue-green deployments with SSM active-slot switching
- Layered secrets pipeline: SSM KMS-encrypted → Secrets Manager → ECS runtime injection
- Dual observability: **Prometheus + Grafana + CloudWatch**; Fargate Spot dev environments with 30-min TTL — cost per run: **~$0.02**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=FF9900)
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

---

### [EC2-Docker-Pipeline — 3-Tier Application on AWS](https://github.com/harshit-kandhwey/ec2-docker-pipeline)

> Full 3-tier app (React + Node.js + MongoDB) deployed on AWS with IaC and automated CI/CD

- Terraform-provisioned VPC, EC2, and IAM; Docker Compose for service orchestration
- GitHub Actions CI/CD with SSH deploy, Docker rebuild, and health checks — **full deploy in ~2–3 min**
- Security hardening: IP-restricted SSH, EBS encryption, IMDSv2, least-privilege IAM, secrets via GitHub Secrets

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=FF9900)
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

---

## 📈 Impact at a Glance

| Metric | Result |
|---|---|
| Annual cloud savings delivered | **$200K+** |
| Manual pre-migration effort reduced | **70%** |
| Servers automated & validated | **500+** |
| Uptime SLA maintained | **99.5%** |
| Infrastructure assessments conducted | **200+** |

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=harshit-kandhwey&show_icons=true&theme=dark&hide_border=true&count_private=true" height="150" alt="GitHub Stats"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=harshit-kandhwey&layout=compact&theme=dark&hide_border=true" height="150" alt="Top Languages"/>

</div>

---

## 🏅 Certifications

<a href="https://www.credly.com/badges/fa8ddffb-6007-4d5d-a265-e1d257d02229/public_url" target="_blank">
  <img src="https://img.shields.io/badge/AWS-Solutions_Architect_Associate-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS SAA"/>
</a>
&nbsp;
<a href="https://www.credly.com/badges/1f26df72-2ef1-42a8-900e-30ac35d8ff78/public_url" target="_blank">
  <img src="https://img.shields.io/badge/AWS-Cloud_Practitioner-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS CCP"/>
</a>

---

## 🐍 Contribution Graph

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/harshit-kandhwey/harshit-kandhwey/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/harshit-kandhwey/harshit-kandhwey/output/github-snake.svg">
  <img alt="GitHub contribution snake animation" src="https://raw.githubusercontent.com/harshit-kandhwey/harshit-kandhwey/output/github-snake.svg">
</picture>

---

## 📬 Let's Connect

<a href="https://linkedin.com/in/harshitkandhwey" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-harshitkandhwey-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="mailto:harshitkandhwey@outlook.com">
  <img src="https://img.shields.io/badge/Email-harshitkandhwey@outlook.com-0078D4?style=for-the-badge&logo=microsoft-outlook&logoColor=white"/>
</a>

---

<div align="center">
<sub>Bangalore, India · Open to senior DevOps / Cloud Engineer roles</sub>
</div>
