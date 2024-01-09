# Kubernetes

### Run this commands to create the services

```
kubectl apply -f account-service-dev.yaml
kubectl apply -f account-service.yaml
kubectl apply -f mongodb-dev.yaml
kubectl apply -f mongodb-service.yaml
kubectl apply -f tracking-service-configmap.yaml
kubectl apply -f tracking-service-dev.yaml
kubectl apply -f tracking-service.yaml
```

### Check every thing is fine

`kubectl get pods`  
All have to be running successfully
