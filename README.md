# Kubernetes Learning & Production Microservices Project

This repository contains my hands-on Kubernetes learning journey and the
Kubernetes resources I build while developing a production-style
microservices architecture.

## 🎯 Goal

The goal of this project is to move from Kubernetes fundamentals to
production-level Kubernetes concepts and deployment practices.

## 🛠️ Technologies

- Kubernetes
- Kind
- Docker
- kubectl
- NGINX Ingress Controller
- YAML
- Git & GitHub

## 📚 Topics Completed

### Kubernetes Fundamentals

- Kubernetes Cluster
- Nodes
- Pods
- Deployments
- ReplicaSets
- Self-Healing
- Labels and Selectors
- Services
- Declarative YAML

### Application Configuration

- ConfigMaps
- Secrets
- Environment Variables
- ConfigMap Volume Mounts

### Storage

- StorageClass
- PersistentVolume
- PersistentVolumeClaim
- Persistent Storage
- `ReadWriteOnce`

### Application Deployment

- Rolling Updates
- Rollbacks
- Deployment Revision History

### Networking

- Kubernetes Services
- Ingress
- NGINX Ingress Controller
- Host-based Routing
- Kind Port Mapping
- External Traffic → Ingress → Service → Pod

## 📁 Repository Structure

```text
Kubernetes/
│
├── README.md
├── .gitignore
│
├── kind-config.yaml
├── deployment.yaml
├── nginx-ingress.yaml
│
├── configmap-pod.yaml
├── secret-pod.yaml
│
├── pvc.yaml
└── storage-pod.yaml