# 🚀 DevOps Project: Docker + Kubernetes

## 🔧 Tech Stack
- Docker
- Kubernetes (Minikube)
- Nginx

## 📌 What I Did
- Containerized a web app using Docker
- Deployed it locally using Kubernetes
- Exposed the service via NodePort

## 🖥️ Commands Used
```bash
docker build -t myapp .
kubectl create deployment myapp --image=myapp
kubectl expose deployment myapp --type=NodePort --port=80
