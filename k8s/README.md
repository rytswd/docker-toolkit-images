# Using Toolkit in Kubernetes

If you want to deploy a basic toolkit for debugging, testing, etc., you can use the predefined YAMLs here.

### Alpine

```bash
$ kubectl apply \
    -f https://raw.githubusercontent.com/rytswd/docker-toolkit-images/main/k8s/toolkit-alpine.yaml
```

### Buster

```bash
$ kubectl apply \
    -f https://raw.githubusercontent.com/rytswd/docker-toolkit-images/main/k8s/toolkit-buster.yaml
```
