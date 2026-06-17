# Cloud Pizza 

A Flask-based pizza ordering application containerized with Docker and deployed on Kubernetes.

## Features
- Order pizza through a web interface
- Dockerized application
- Kubernetes Deployment
- Kubernetes Service using NodePort
- Scalable containerized architecture

## Tech Stack
- Python
- Flask
- Docker
- Kubernetes

## Run with Docker

docker build -t cloud-pizza .
docker run -p 5000:5000 cloud-pizza

## Kubernetes Deployment

kubectl apply -f deployment.yaml
kubectl apply -f service.yaml

## Verify

kubectl get pods
kubectl get svc

## Author

Nayan Sawant
