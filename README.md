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

## Screenshot minh họa

### 1. 5 Pods đang chạy sau khi scale
![5 Pods running](screenshots/pods-5-running.png)

### 2. Minikube Dashboard
![Minikube Dashboard](screenshots/minikube-dashboard.png)

### 3. Trang web tùy chỉnh bằng ConfigMap (nếu có)
![Custom page](screenshots/custom-page-configmap.png)
