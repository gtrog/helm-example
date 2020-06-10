# helm-example
Installing:

With values file
```
helm install my-nginx nginx --values nginx/values/qa.yaml
```

With explicit values
```
helm install my-nginx nginx --set tag=latest
```

Upgrading once already installed
```
helm upgrade my-nginx nginx --set tag=latest
```

Removing
```
helm uninstall my-nginx
```
