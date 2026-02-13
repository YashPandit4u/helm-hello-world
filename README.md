# helm-hello-world

Install the ingress controller using:

```
helm repo add ingress-nginx https://kubernetes.github.io/ingress-nginx
helm install ingress-nginx ingress-nginx/ingress-nginx --create-namespace --namespace ingress-nginx
```

Install this helm using:
```
helm install helm-release-dev .
```

To uninstall this helm chart:
```
helm uninstall helm-release-dev
```

List all installed helm charts:
```
helm list
helm list -A
```

Upgrade after changing something:
```
helm upgrade helm-hello-world-dev .
```