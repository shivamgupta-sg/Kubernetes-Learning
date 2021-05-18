# MINIKUBE COAMMANDS

## Start a cluster:-

```
minikube start
```

## Access the Kubernetes Dashboard:-

```
minikube dashboard
```

## Update our cluster:-
```
minikube start --kubernetes-version=latest
```

## Start a second local cluster:-

```
minikube start -p cluster2
```

## Stop A local Cluster:-
```
minikube stop
```

## Delete a local cluster:-

```
minikube delete
```
## Status of the minikube cluster :-
```
minikube status
```

## Version of minikube using
```
minikube version
```

## Allocate memory And Cpu's:-

```
minikube start --cpus 4 --memory 8192
```

## Get information regarding where your Kubernetes master is running at, CoreDNS is running at, kubernetes-dasboard is running at, we use:-

```
kubectl cluster-info
```
