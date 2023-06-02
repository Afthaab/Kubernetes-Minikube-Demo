# Kubernetes-Minikube-Demo
This repo consist of kubernetes depoly and pod file. 

## Kubernetes Pods
A pod is the smallest execution unit in Kubernetes. A pod encapsulates one or more applications. Pods are ephemeral by nature, if a pod (or the node it executes on) fails, Kubernetes can automatically create a new replica of that pod to continue operations. Pods include one or more containers (such as Docker containers).

## Command to run Pod.yaml
```
kubectl apply -f pod.yaml
```

## Command to run Kubernetes Deploy
```
kubectl apply -f deploy.yaml
```
This will do the Auto healing of the Pods. And the load can also be balanced with building multiple replicas

