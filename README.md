# Prometheus & Grafana Monitoring Stack Setup

This repository contains step-by-step documentation for deploying and configuring Prometheus and Grafana on Kubernetes (EKS / Minikube).

---

## 1. Prerequisites

Ensure you have the following installed and configured before proceeding:
- **Kubernetes Cluster** (AWS EKS or local Minikube)
- **kubectl CLI** configured to communicate with your cluster
- **Helm v3+** installed

---

## 2. Installation Steps

### Step 1 — Add Helm Repository
Add the official Prometheus community Helm repository and update it:
```bash
helm repo add prometheus-community [https://prometheus-community.github.io/helm-charts](https://prometheus-community.github.io/helm-charts)
helm repo update