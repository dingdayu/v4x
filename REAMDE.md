# v4x

A Xboard Helm chart for Kubernetes.

## Pre

Creat a .env file (installed .env).

```bash
kubectl create secret generic v4x --from-env-file=.env
```

> Add `--namespace=my-namespace` option set namespace for kubernetes.

## Use

Add helm repo:

```bash
helm repo add v4x https://dingdayu.github.io/v4x
helm repo update
```

Install Xboard to Kubernetes.

```bash
helm install x4x v4x/xboard
```
