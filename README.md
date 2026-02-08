# helm-hello-world

Install the ingress controller using:

```
helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx
helm install ingress-nginx ingress-nginx/ingress-nginx --create-namespace --namespace ingress-nginx
```

Install this helm using:
```
helm install helm-release-1 .
```