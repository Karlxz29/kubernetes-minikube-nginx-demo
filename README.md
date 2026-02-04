# Kubernetes Minikube Nginx Demo

Dự án thực hành Kubernetes cơ bản với Minikube.

## Mô tả
- Deploy Nginx web server lên Minikube
- Sử dụng Deployment và Service NodePort
- Thử nghiệm scale, self-healing, ConfigMap

## Công nghệ
- Minikube
- kubectl
- Docker (nginx:latest)

## Hướng dẫn chạy
1. minikube start --driver=hyperkit
2. kubectl apply -f deployment.yaml
3. kubectl apply -f service.yaml
4. minikube service nginx-service


<img width="449" height="137" alt="screenshots:pods-5-running" src="https://github.com/user-attachments/assets/e0ae6a33-7767-48cc-93d4-0ce9355c6f21" />
