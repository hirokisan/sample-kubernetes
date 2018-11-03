# sample-kubernetes

## Requirements
* [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
* [kubernetes/minikube](https://github.com/kubernetes/minikube)

## Create
```
$ kubectl apply -f deploy.yml
$ kubectl apply -f server.yml
```

## Delete
```
$ kubectl delete -f deploy.yml
$ kubectl delete -f server.yml
```

## Pod list
```
$ kubectl get pods
```

## Service list
```
$ kubectl get services
```

## Access
```
$ minikube service web-server
$ minikube dashboard
```
