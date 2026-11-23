### Hi, I'm Aditya 👋

**Senior Cloud Infrastructure & Site Reliability Engineer** — I build and run resilient, cost-optimized, observable AWS platforms.

- 🔭 **Focus:** AWS platform reliability, Kubernetes (EKS) and ECS orchestration, OpenTelemetry observability pipelines, FinOps
- 🛠️ **Core stack:** AWS (EKS, ECS/Fargate, EC2, VPC, Transit Gateway, IAM, Aurora, DynamoDB, S3, SQS, SNS, Lambda), Terraform, Kubernetes, Docker, Jenkins, Linux (AL2023)
- 📊 **Observability:** OpenTelemetry, Prometheus, Grafana, Splunk, CloudWatch, SLO/SLI
- 📍 **Location:** Toronto, Ontario, Canada

---

### 🚀 Featured Work

- **Observability modernization.** Migrated legacy monitoring agents to OpenTelemetry Collectors with unified routing to Prometheus, Grafana, and Splunk.
- **Golden images and CI/CD acceleration.** CIS-hardened Amazon Linux 2023 AMIs built with Packer and Ansible; Jenkins Docker build images cut from 8 GB to 250 MB, cutting build times from 8 minutes to 2.
- **Planet-scale geospatial infrastructure.** Full-planet (~1.65 TB) Nominatim PostgreSQL/PostGIS cluster on AWS EC2/EBS.
- **Platform at scale.** 40+ ECS clusters across 20+ AWS accounts.

---

### 🧰 Technical Toolkit

**Cloud & Infrastructure as Code**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Linux](https://img.shields.io/badge/Amazon_Linux_2023-FCC624?style=flat-square&logo=linux&logoColor=black)

**Containers, Orchestration & CI/CD**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Amazon EKS](https://img.shields.io/badge/Amazon_EKS-FF9900?style=flat-square&logo=amazoneks&logoColor=white)
![Amazon ECS](https://img.shields.io/badge/Amazon_ECS-FF9900?style=flat-square&logo=amazonecs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)

**Observability & Monitoring**

![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)

**Languages & Automation**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

---

### 📦 Terraform Modules

Reusable AWS modules, each with CI running `terraform fmt`, `validate`, and `terraform test`.

- [terraform_eks](https://github.com/adityapidikiti/terraform_eks) — EKS cluster with ALB ingress, CloudWatch logging, metrics server, Prometheus/Grafana and KEDA autoscaling
- [terraform_ecs](https://github.com/adityapidikiti/terraform_ecs) — containerised app on ECS Fargate behind an ALB, with VPC, autoscaling and HTTPS
- [terraform_aurora_module](https://github.com/adityapidikiti/terraform_aurora_module) — Aurora cluster with subnet and parameter groups
- [terraform_dynamodb_module](https://github.com/adityapidikiti/terraform_dynamodb_module) — DynamoDB tables with GSIs/LSIs, autoscaling, PITR and encryption
- [terraform_elasticache_module](https://github.com/adityapidikiti/terraform_elasticache_module) — ElastiCache replication groups, Redis or Valkey, single-node or cluster mode
- [terraform_lambda_module](https://github.com/adityapidikiti/terraform_lambda_module) — Lambda functions from a zip package or container image
- [terraform_s3_bucket_module](https://github.com/adityapidikiti/terraform_s3_bucket_module) — S3 buckets with secure defaults and optional lifecycle, CORS and logging
- [terraform_sqs_queue_module](https://github.com/adityapidikiti/terraform_sqs_queue_module) — SQS queues with dead-letter redrive and optional encryption
- [terraform_sns_topic_module](https://github.com/adityapidikiti/terraform_sns_topic_module) — SNS topics with subscriptions and optional KMS
