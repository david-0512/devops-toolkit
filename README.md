# DevOps Infrastructure Toolkit

A collection of infrastructure-as-code templates, Kubernetes manifests, and automation scripts used for real-world DevOps tasks and cloud deployments. This repo reflects my 13+ years of experience in Linux system administration, CI/CD, and cloud infrastructure engineering.

---

## 🔧 Contents

### 1. `terraform/`
Infrastructure provisioning scripts:
- `aws-ecs-cluster/` — Terraform modules for ECS cluster setup
- `aws-vpc-rds/` — VPC, RDS PostgreSQL, NAT Gateway configs
- `aliyun-ecs/` — Provision Alibaba Cloud ECS instances with security groups

### 2. `ansible/`
- `server-init.yml` — Linux baseline hardening + firewall setup
- `deploy-lamp.yml` — LAMP stack deployment for staging/production
- `k8s-bootstrap.yml` — Initialize K8s nodes with CRI + kubeadm

### 3. `kubernetes/`
K8s manifests and Helm charts:
- `nginx-deployment.yaml`
- `monitoring-stack/` (Prometheus + Grafana + Node Exporter)
- `ethereum-node/` (Erigon + persistent volumes)

### 4. `ci-cd/`
CI/CD automation examples:
- `jenkins-pipeline.groovy` — Multi-stage build/test/deploy
- `gitlab-ci.yml` — K8s deployment with Helm + rollback

---

## 🛠 Tools & Technologies
- AWS, Alibaba Cloud
- Terraform, Ansible, Pulumi
- Kubernetes, Docker, Helm
- Jenkins, GitLab CI
- Prometheus, Grafana, ELK

---

## 📦 How to Use

```bash
cd terraform/aws-vpc-rds
terraform init && terraform apply
```

```bash
ansible-playbook ansible/server-init.yml -i hosts.ini
```

---

## 👨‍💻 Author
**Guo Jianrui**  
DevOps Engineer | Cloud Architect | Infrastructure-as-Code Enthusiast

🔗 [GitHub](https://github.com/yourusername) | 🇯🇵 Based in Japan (UTC+9)

---

## 📄 License
MIT License — feel free to use or fork.

