# Kube-JS-Server

### 1. First you should run server-dep.yaml

```sh
$ kubectl apply -f server-dep.yaml
```
### 2. List down all the deployments and pods

```sh
$ kubectl get deployments
$ kubectl get pods
```

### 3. After you should run server-svc.yaml 

```sh
$ kubectl apply -f server-svc.yaml
```

### 4. List all the services


```sh
$ kubectl get svc
```
We use NodePort type to expose service.

```sh
$ curl -i nodeIp:nodePort
```
