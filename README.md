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
