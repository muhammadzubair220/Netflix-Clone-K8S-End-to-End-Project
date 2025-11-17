# 🎬 Netflix Clone - DevSecOps Project
[![LinkedIn](https://img.shields.io/badge/Connect%20with%20me%20on-LinkedIn-blue.svg)](https://www.linkedin.com/in/muhammadzubair220/)
[![GitHub](https://img.shields.io/github/stars/muhammadzubair220.svg?style=social)](https://github.com/muhammadzubair220)
[![AWS](https://img.shields.io/badge/AWS-%F0%9F%9B%A1-orange)](https://aws.amazon.com)
[![Terraform](https://img.shields.io/badge/Terraform-%E2%9C%A8-lightgrey)](https://www.terraform.io)

![Architecture Diagram](assets/arch-diag.gif)


A **complete end-to-end DevSecOps project** showcasing how to automate, secure, and monitor infrastructure and applications using modern tools — from **Terraform to Kubernetes**, **Jenkins to Trivy**, and everything in between.  

Built to demonstrate **real-world DevSecOps workflows** for CI/CD, cloud automation, security integration, and observability — all in one Netflix-themed application. 🍿  

---

## 🚀 Project Overview

This project simulates a real enterprise-grade setup where a **React-based Netflix Clone** is deployed and managed through a **secure, automated DevOps pipeline**.

### 🌐 Key Features
- **Infrastructure as Code** with Terraform (AWS provisioning)
- **State management** using Terraform Cloud  
- **CI/CD automation** with GitHub Actions and Jenkins  
- **Security Scanning** with Trivy & OWASP Dependency Check  
- **Containerization** with Docker  
- **Kubernetes Deployment** (unmanaged cluster setup)  
- **Monitoring Stack** for Jenkins, Kubernetes, and the app itself  

---

## 🧩 Directory Structure
```bash
.
├── Application-Code        # Frontend Netflix Clone app built with React + Vite
│   ├── Dockerfile           # Docker image build instructions
│   ├── package.json         # Dependencies and scripts
│   ├── src/                 # Main source code
│   └── public/              # Static assets
│
├── Jenkins
│   └── Jenkinsfile          # CI/CD pipeline configuration (build → test → deploy)
│
├── Kubernetes
│   ├── deployment.yml       # App deployment manifest
│   └── service.yml          # K8s service exposure
│
└── Terraform
    ├── main.tf              # AWS resource definitions
    ├── backend.tf           # Terraform Cloud backend configuration
    ├── iam.tf               # IAM roles and policies
    ├── vpc.tf               # Network setup
    ├── variables.tf         # Input variables
    ├── dev.auto.tfvars      # Environment variables
    └── gather.tf            # Data sources and dependencies
```

## 🛠️ Tech Stack

| Category | Tools / Technologies |
|-----------|----------------------|
| **Infrastructure** | Terraform, AWS EC2, Terraform Cloud |
| **CI/CD** | Jenkins, GitHub Actions |
| **Security** | Trivy, SonarQube, OWASP Dependency Check |
| **Containerization** | Docker |
| **Orchestration** | Kubernetes (Unmanaged Cluster) |
| **Monitoring** | Node Exporter, Prometheus, Kube State Metrics |
| **Frontend** | React, Vite, TMDB API |

---

## 🎯 Objectives

1. Automate the entire infrastructure and application deployment lifecycle  
2. Integrate security and quality checks early in the pipeline  
3. Establish a fully observable, monitored system for reliability  
4. Showcase end-to-end DevSecOps workflow — ideal for portfolio and interviews  

---

## 📽️ Project Implementation

This project demonstrates a complete DevSecOps workflow with the following phases:

| Phase | Focus Area | Key Components |
|------|--------|-------------|
| 🧩 **Phase 1** | *Infrastructure Setup* | Terraform + GitHub Actions + AWS |
| ⚙️ **Phase 2** | *CI/CD Pipeline* | Jenkins, Docker, SonarQube, Trivy |
| 🧠 **Phase 3** | *Security Integration* | SonarQube + Trivy + TMDB API |
| ☸️ **Phase 4** | *Kubernetes Deployment* | Cluster setup + App deployment |
| 📊 **Phase 5** | *Monitoring & Observability* | Prometheus + Grafana |

---

## 🧑‍💻 Author

**Muhammad Zubair**  
DevOps & Cloud Engineer  
🔗 [LinkedIn](https://www.linkedin.com/in/muhammadzubair220/)

---

## Contributing
We welcome contributions! If you have ideas for enhancements or find any issues, please open a pull request or file an issue.

## License
This project is licensed under the [MIT License](LICENSE).

Happy Coding! 🚀
