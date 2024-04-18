# Commands to deploy a MERN app using Kubernetes

## Installation
- Install kubectl
- Install minikube

## Commands
```bash
minikube start
kubectl apply -f mongo-secret.yaml
kubectl apply -f mongo-config.yaml
kubectl apply -f mongo-app.yaml
kubectl apply -f web-app.yaml
kubectl get pod -o wide
kubectl get svc
kubectl get configmap
kubectl get deployment
minikube ip
```
```bash
minicube service webapp-service
```
++++++++++++++++++++++++++++++++++++++++++++

```bash
kubectl delete deployment --all
kubectl delete secret --all
kubectl delete configmap --all
kubectl selete svc --all
```

``` bash
minikube stop
```