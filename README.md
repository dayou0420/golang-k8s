# Golang Kubernetes
```terminal
$ docker build -t golang:latest .
```
```terminal
$ docker tag golang:latest jianghong0420/golang:1.0.0
```
```terminal
$ docker push jianghong0420/golang:1.0.0
```
```terminal
$ kubectl apply -f deployment.yml
```
```terminal
$ kubectl get pods
```
```terminal
$ kubectl port-forward golang-xx 8080:8080
```
```terminal
$ kubectl logs -f golang-xx
```
```terminal
$ kubectl apply -f .
```
```terminal
$ kubectl get services
```
```terminal
$ minikube service golang-service --url
```
```terminal
$ kubectl delete service golang-service
```
```terminal
$ kubectl delete deployment golang
```
```terminal
$ minikube stop
```
```terminal
$ minikube delete
```
