# sample-kubernetes

## Requirements
* [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
* [kubernetes/minikube](https://github.com/kubernetes/minikube)

## Create
```
$ kubectl apply -f deploy.yml
$ kubectl apply -f service.yml
```

## Delete
```
$ kubectl delete -f deploy.yml
$ kubectl delete -f service.yml
```

## Pod list
```
$ kubectl get pods
```

## Service list
```
$ kubectl get services

$ minikube service list
```

## Access
```
$ minikube service web-server
$ minikube dashboard
```
