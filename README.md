# GitOps Kubernetes Demo

This repository contains Kubernetes manifests used for the GitOps learning lab.

## 📁 Files

- `deployment.yaml` — creates the NGINX Deployment
- `service.yaml` — creates the NGINX ClusterIP Service

## 🏗️ Application

The application uses the official NGINX container image.

## 🚀 Kubernetes Resources

The repository contains:

- Deployment
- Service

## 🔄 GitOps Flow

```text
GitHub
   ↓
Argo CD
   ↓
Kubernetes
