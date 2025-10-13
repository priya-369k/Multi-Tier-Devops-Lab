# vprofile-local-stack-setup
Multi-tier Java web application stack for DevOps practice using Vagrant, VirtualBox, and shell provisioning.

## 🚀 Tech Stack

- **Nginx** – Load Balancer & Reverse Proxy  
- **Apache Tomcat** – Java Application Server  
- **MySQL** – Relational Database  
- **Memcached** – Caching Layer  
- **RabbitMQ** – Message Broker (non-functional placeholder)  
- **Vagrant + VirtualBox** – Infrastructure Automation  
- **Shell Scripting** – Provisioning & Configuration

## 📦 Architecture Overview

[Browser] → [Nginx] → [Tomcat] → [Memcached] → [MySQL] ↓ [RabbitMQ]


## 🧠 Learning Objectives

- Infrastructure as Code (IaC)
- Multi-tier architecture setup
- Service orchestration and automation
- Troubleshooting distributed systems
- Foundation for cloud, container, and CI/CD workflows

## 🛠️ Setup Instructions

```bash
# Prerequisites
Install VirtualBox, Vagrant, Git Bash (Windows), and a text editor

# Clone the repo
git clone https://github.com/priya-369k/vprofile-local-stack-setup.git
cd vprofile-local-stack-setup/vagrant

# Start the stack
vagrant up

✅ Validation Checklist
- [x] Homepage loads via Nginx
- [x] User registration and login work
- [x] Data persists across sessions
- [x] Services communicate correctly
- [x] No errors in logs


📚 Future Enhancements
- Dockerize each service
- Deploy on Kubernetes
- Add CI/CD pipeline (GitHub Actions)
- Integrate monitoring (Prometheus/Grafana)
- Secure with SSL/TLS and secrets management

<img width="940" height="598" alt="image" src="https://github.com/user-attachments/assets/a71b0008-48d5-45ad-bee0-1c5b60ed2c6d" />



