# kubernetes
Exemplos kubernetes

## Kind

```shell
kind create cluster --config kind.yaml --name meucluster
```

```shell
kind get clusters
```

```shell
kubectl get nodes
```

## Pod

```shell
kubectl apply -f pod.yaml
```

```shell
kubectl get pods
```

```shell
kubectl port-forward pod/goserver 8080:80
```

## ReplicaSet

```shell
kubectl apply -f replica_set.yaml 
```

```shell
kubectl get replicasets
```

```shell
kubectl port-forward replicasets/goserver 8080:80
```
