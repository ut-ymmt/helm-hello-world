# Kind(Kubernetes in Docker)

## Create Cluster
```bash
kind create cluster --name 1.14-local --image kindest/node:v1.14.3 --config multinode.yaml
```

## Install Tiller
```bash
kubectl apply -f manifest/tiller/tiller.yaml
```
