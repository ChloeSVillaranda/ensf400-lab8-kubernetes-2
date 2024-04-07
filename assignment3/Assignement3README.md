## Steps Taken
Here are the following steps, commands, and outputs:

### Initialization

```sh
minikube start
minikube addons enable ingress
```

### Deployment
Had to deply all .yaml files
```sh
kubectl apply -f nginx-dep.yaml
kubectl apply -f nginx-configmap.yaml
kubectl apply -f nginx-svc.yaml
kubectl apply -f nginx-ingress.yaml 
kubectl apply -f app-1-svc.yaml
kubectl apply -f app-1-ingress.yaml
kubectl apply -f app-1-dep.yaml
kubectl apply -f app-2-svc.yaml
kubectl apply -f app-2-ingress.yaml
kubectl apply -f app-2-dep.yaml

```

