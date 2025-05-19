
# 🚀 DevOps Internship - Task 5: Kubernetes Cluster using Minikube

## Objective
Deploy a sample NGINX app using Kubernetes with Minikube locally.

## Steps

1. Installed Minikube and kubectl
2. Started Minikube using:
   ```bash
   minikube start --driver=docker
Created a Deployment (deployment.yaml)

Exposed it with a Service (service.yaml)

Used kubectl to verify:

kubectl get pods

kubectl get services

kubectl describe pod

Scaled using:

bash
Copy
Edit
kubectl scale deployment nginx-deployment --replicas=4
Updated using:

bash
Copy
Edit
kubectl set image deployment/nginx-deployment nginx=nginx:1.25
Files Included
deployment.yaml

service.yaml

screenshots/

README.md

yaml
Copy
