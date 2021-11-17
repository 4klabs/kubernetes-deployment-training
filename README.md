# Kubernetes 101

![K8s](https://fabiosilvabuzina.files.wordpress.com/2019/01/kubernetes-horizontal-color.png)

## Build and push image

```sh
docker build . -t <user>/helloworld
docker push <user>/helloworld
```

## Create local cluster

```sh
k3d cluster create my_cluster
```

## Create pod

```sh
kubectl apply -f k8s
```
