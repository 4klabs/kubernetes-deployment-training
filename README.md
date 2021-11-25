# Kubernetes Training

> An Introduction to Kubernetes Deployments, Services, and Ingress

## Overview

![Overview](https://matthewpalmer.net/kubernetes-app-developer/articles/nodeport.png)

## Build and push image

```sh
docker build . -t <user>/helloworld
docker push <user>/helloworld
```

## Create local cluster

```sh
k3d cluster create my_cluster
```

## Apply manifests

```sh
kubectl apply -f k8s
```
