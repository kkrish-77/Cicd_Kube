# ✅ GKE TODO App with GitHub Actions CI/CD

## 🚀 Project Highlights

<p align="left">
  <img src="https://img.shields.io/badge/Like-👍-blueviolet?style=for-the-badge&logo=github" alt="Like Badge" />
  <img src="https://img.shields.io/badge/GKE-Deployed-success?style=for-the-badge&logo=googlecloud" alt="GKE Deployed" />
  <img src="https://img.shields.io/badge/CI/CD-GitHub%20Actions-blue?style=for-the-badge&logo=githubactions" alt="CI/CD" />
  <img src="https://img.shields.io/badge/SSL-TLS-green?style=for-the-badge&logo=letsencrypt" alt="SSL Secured" />
</p>


---

## 🧾 Project Overview

This is a **frontend-only TODO application** that connects directly to a hosted SQL database (like Supabase or PostgreSQL). The app is:

- 🚀 Deployed on **Google Kubernetes Engine (GKE)**
- 🔁 Automatically deployed using **GitHub Actions CI/CD**
- 🌐 Exposed with **NGINX Ingress Controller**
- 🔐 Secured via **Let's Encrypt TLS**
- 🌍 Mapped to a **custom domain**

---

## 🎥 Demo

https://github.com/user-attachments/assets/888a5ce0-4664-4169-b06d-a2931bb90a73

---

## ⚙️ Tech Stack

- 💻 Frontend: Next.js
- 🗃️ SQL Database: PostgreSQL
- ☸️ Kubernetes (GKE)
- 🐳 Docker
- 🌀 NGINX Ingress
- 🔐 cert-manager + TLS
- 🛠️ GitHub Actions

---

## 📁 Project Structure

```bash
.
├── .github/workflows/deploy.yml    # GitHub Actions pipeline
├── k8s/
│   ├── deployment.yaml
│   ├── service.yaml
│   ├── ingress.yaml
│   ├── cluster-issuer.yaml
│   └── tls-secret.yaml
├── Dockerfile
├── public/
├── src/
├── README.md
