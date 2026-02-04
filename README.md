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
<img width="449" height="137" alt="screenshots:pods-5-running" src="https://github.com/user-attachments/assets/e0ae6a33-7767-48cc-93d4-0ce9355c6f21" />

### 2. Minikube Dashboard
<img width="1920" height="1080" alt="screenshots:minikube-dashboard" src="https://github.com/user-attachments/assets/2badf57a-7cac-4c83-b703-81246830997e" />

### 3. Trang web tùy chỉnh bằng ConfigMap
<img width="3840" height="2160" alt="screenshots:custom-page-configmap" src="https://github.com/user-attachments/assets/7b3c027d-d218-4559-8124-b76dcd2e8174" />
