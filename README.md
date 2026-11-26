# Kubernetes Practical Assessment

## Project Overview
This project demonstrates Kubernetes resource management using Minikube and kubectl.

## Technologies Used
- Kubernetes
- Minikube
- kubectl
- Docker
- Nginx
- YAML

## Tasks Completed

1. Installed Minikube, Kubernetes and kubectl.
2. Created a namespace and Nginx Deployment.
3. Exposed the Deployment using ClusterIP and NodePort Services.
4. Configured ConfigMap and Secret.
5. Created PersistentVolume and PersistentVolumeClaim.
6. Scaled Deployment replicas from 2 to 4.
7. Performed Rolling Update and Rollback.
8. Verified Kubernetes resources.

## Kubernetes Resources

- Namespace: devops
- Deployment: nginx-deployment
- Replicas: 4
- ClusterIP Service: nginx-service
- NodePort Service: nginx-nodeport
- NodePort: 30080
- PersistentVolume: nginx-pv
- PersistentVolumeClaim: nginx-pvc
- ConfigMap: app-config
- Secret: app-secret

## How to Run

Start Minikube:

```bash
minikube start --driver=docker
