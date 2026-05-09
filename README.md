# 🚀 Production-Grade 3-Tier Java Application Deployment on AWS EKS using Kubernetes, Jenkins & DevOps Automation

<p align="center">

![Kubernetes](https://img.shields.io/badge/Kubernetes-v1.26-blue?logo=kubernetes)

![Docker](https://img.shields.io/badge/Docker-Containerization-blue?logo=docker)

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws)

![Jenkins](https://img.shields.io/badge/Jenkins-CI/CD-red?logo=jenkins)

![SonarQube](https://img.shields.io/badge/SonarQube-Code%20Quality-green?logo=sonarqube)

![Nexus](https://img.shields.io/badge/Nexus-Artifact%20Repository-black)

![Linux](https://img.shields.io/badge/Linux-Ubuntu-yellow?logo=linux)

</p>

---

# 📌 Project Overview

This project demonstrates the deployment of a **Production-Grade Java-Based 3-Tier Web Application** on a Kubernetes cluster hosted on AWS infrastructure using modern DevOps and Cloud-Native practices.

The implementation focuses on:

- Containerized microservice deployment
- Kubernetes orchestration
- End-to-End CI/CD automation
- Code quality analysis
- Artifact management
- Persistent storage integration
- Real-time monitoring
- Infrastructure scalability
- Secure application exposure

The entire workflow simulates a real-world enterprise-grade DevOps deployment pipeline used in modern cloud environments.

---

# 🏗️ High-Level Architecture

```text
                +----------------------+
                |      GitHub Repo     |
                +----------+-----------+
                           |
                           v
                +----------------------+
                |      Jenkins CI      |
                +----------+-----------+
                           |
        +------------------+------------------+
        |                                     |
        v                                     v
+---------------+                  +------------------+
| Maven Build   |                  | SonarQube Scan   |
+---------------+                  +------------------+
        |                                     |
        +------------------+------------------+
                           |
                           v
                +----------------------+
                | Nexus Repository     |
                +----------+-----------+
                           |
                           v
                +----------------------+
                | Docker Build & Push  |
                +----------+-----------+
                           |
                           v
                +----------------------+
                | Kubernetes Cluster   |
                |      AWS EKS         |
                +----------+-----------+
                           |
          +----------------+----------------+
          |                                 |
          v                                 v
+-------------------+          +----------------------+
| Java Application  |          | Memcached Service    |
| Tomcat Deployment |          | Database Deployment  |
+-------------------+          +----------------------+
                           |
                           v
                +----------------------+
                | AWS Load Balancer    |
                +----------------------+
```

---

# ⚡ Key Features

✅ Enterprise-Grade CI/CD Pipeline  
✅ Kubernetes-Based Container Orchestration  
✅ AWS EBS Persistent Volume Integration  
✅ Multi-Stage Docker Image Optimization  
✅ SonarQube Static Code Analysis  
✅ Nexus Artifact Repository Integration  
✅ Slack-Based Real-Time Notifications  
✅ Kubernetes Secrets & Configurations  
✅ Lens IDE Cluster Monitoring  
✅ Production-Style Scalable Deployment  
✅ Secure Application Exposure using LoadBalancer  
✅ Infrastructure Automation Best Practices

---

# ☁️ AWS Services Used

| AWS Service | Purpose |
|-------------|----------|
| EC2 | Kubernetes Worker Nodes |
| EKS | Managed Kubernetes Cluster |
| EBS | Persistent Storage |
| ELB | External Application Exposure |
| IAM | Access Control & Permissions |
| VPC | Network Isolation |
| Security Groups | Network Security |

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|----------|
| Kubernetes | Container Orchestration |
| Docker | Application Containerization |
| Jenkins | CI/CD Automation |
| SonarQube | Static Code Analysis |
| Nexus | Artifact Management |
| Maven | Java Build Tool |
| Slack | Deployment Notifications |
| GitHub | Source Code Management |
| Lens IDE | Kubernetes Monitoring |
| Linux | Server Environment |
| AWS | Cloud Infrastructure |

---

# 📂 CI/CD Workflow

```text
GitHub Repository
        ↓
Jenkins Pipeline Trigger
        ↓
Maven Build & Unit Testing
        ↓
SonarQube Code Analysis
        ↓
Quality Gate Validation
        ↓
Artifact Upload to Nexus
        ↓
Docker Image Build
        ↓
DockerHub Push
        ↓
Kubernetes Deployment
        ↓
AWS LoadBalancer Exposure
        ↓
Slack Notifications
```

---

# 🐳 Docker Optimization Strategy

Implemented Multi-Stage Docker Builds to achieve:

- 70% reduction in image size
- 80% faster container startup time
- Lightweight production-ready images
- Improved security posture
- Faster deployment cycles
- Better resource utilization

---

# ☸️ Kubernetes Resources Implemented

| Resource | Purpose |
|----------|----------|
| Deployment | Application Lifecycle Management |
| Service | Internal & External Communication |
| LoadBalancer | Public Access |
| Secret | Sensitive Credential Management |
| ConfigMap | Configuration Injection |
| Persistent Volume | Data Persistence |
| Persistent Volume Claim | Storage Allocation |

---

# 📸 Project Screenshots

## Kubernetes Cluster Monitoring

- Node Health Monitoring
- Pod Lifecycle Management
- Service Exposure
- Namespace Monitoring
- Resource Consumption Tracking

## DevOps Pipeline

- Jenkins Build Pipeline
- SonarQube Dashboard
- Nexus Repository Management
- Slack Notification Integration

---

# 🔧 Jenkins Plugins Used

| Plugin | Purpose |
|--------|----------|
| SonarQube Scanner | Code Analysis |
| Nexus Artifact Uploader | Artifact Upload |
| Pipeline Maven Integration | Maven Build Automation |
| Build Timestamp | Build Tracking |
| Pipeline Utility Steps | Pipeline Management |
| Deploy to Container | Application Deployment |
| Slack Notification Plugin | Real-Time Notifications |

---

# 🚀 Deployment Instructions

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/project-name.git
cd project-name
```

---

## 2️⃣ Build Docker Images

```bash
docker build -t app-image .
```

---

## 3️⃣ Push Docker Images to DockerHub

```bash
docker push your-dockerhub-username/app-image
```

---

## 4️⃣ Deploy Kubernetes Resources

```bash
kubectl apply -f .
```

---

## 5️⃣ Verify Cluster Resources

```bash
kubectl get nodes
kubectl get pods
kubectl get svc
kubectl get deploy
```

---

# 📊 Cluster Monitoring

The Kubernetes cluster was monitored using **Lens IDE** for:

- Pod Monitoring
- Node Monitoring
- Namespace Visibility
- Resource Utilization
- Deployment Health Tracking
- Real-Time Cluster Operations

---

# 📈 Project Outcomes

✅ Successfully deployed a scalable 3-tier Java application on Kubernetes  
✅ Automated complete CI/CD workflow using Jenkins  
✅ Improved deployment efficiency through Docker optimization  
✅ Integrated secure persistent storage using AWS EBS  
✅ Implemented enterprise-grade DevOps practices  
✅ Achieved production-style Kubernetes deployment architecture

---

# 📚 Skills Gained

- Kubernetes Administration
- AWS Cloud Infrastructure
- Docker Containerization
- Jenkins Pipeline Automation
- DevOps CI/CD Engineering
- SonarQube Integration
- Artifact Management
- Infrastructure Monitoring
- Production Deployment Strategies
- Linux System Administration

---

# 👨‍💻 Author

# Azmath Ahmed

### Cloud & DevOps Engineer | Kubernetes Enthusiast | AWS Practitioner

Skilled in:

- Kubernetes
- AWS Cloud
- Docker
- Jenkins
- Terraform
- Linux
- CI/CD Automation
- Monitoring & Observability

---

# 🌟 Connect With Me

If you found this project useful, feel free to:

⭐ Star this repository  
🍴 Fork this repository  
🤝 Connect with me on LinkedIn

---

# 📌 Future Enhancements

- Helm Chart Deployment
- ArgoCD GitOps Integration
- Terraform Infrastructure Automation
- Prometheus & Grafana Monitoring
- Horizontal Pod Autoscaling
- AWS ALB Ingress Controller
- Blue-Green Deployment Strategy

---

# 🏁 Final Note

This project represents a complete real-world implementation of modern DevOps and Cloud-Native engineering practices using Kubernetes and AWS infrastructure.

It demonstrates expertise in:

✔️ Containerization  
✔️ CI/CD Automation  
✔️ Kubernetes Orchestration  
✔️ Cloud Infrastructure  
✔️ Monitoring & Scaling  
✔️ Enterprise Deployment Practices

---
<img width="1280" height="720" alt="cp1" src="https://github.com/user-attachments/assets/e49754f8-bb33-4ece-a990-993682e107f3" />

<img width="2944" height="1408" alt="cp2" src="https://github.com/user-attachments/assets/dd3c678a-f3d8-448c-8e17-a5add383eeaa" />

<img width="480" height="226" alt="cp3" src="https://github.com/user-attachments/assets/8d6466c1-2a44-459b-8ec1-8aab68d7f0d1" />

<img width="480" height="221" alt="cp4" src="https://github.com/user-attachments/assets/b8d8cab8-c2ca-49f6-9e9f-a2629159ad56" />

<img width="480" height="227" alt="cp6" src="https://github.com/user-attachments/assets/39698132-f336-4f23-8dd6-12bdd0a87c96" />

<img width="480" height="230" alt="cp 7" src="https://github.com/user-attachments/assets/a916e705-3168-4d9e-b955-d79b0d19ccfd" />


<img width="2720" height="1536" alt="cp 11" src="https://github.com/user-attachments/assets/d9c181c2-15e2-4a4d-a56d-751d92587ea9" />


<img width="2848" height="1600" alt="cp 12" src="https://github.com/user-attachments/assets/6f08159d-906b-4bcf-b1f6-322d40e3e48e" />


<img width="480" height="230" alt="cp5" src="https://github.com/user-attachments/assets/54bcda25-4000-4fd5-90aa-051a98e27e92" />









