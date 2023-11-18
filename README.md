# minio-charts
## operator
### 1.install krew on client node connecting your kubernetes cluster follows this guide
https://krew.sigs.k8s.io/docs/user-guide/setup/install/
### 2.install minio kubectl plugin
```shell
kubectl krew update
kubectl krew install minio
```
### 3.generate resources.yaml
```shell
kubectl minio init --output > resources.yaml
```
### 4.replace the resouces.yaml in the director operator/templates

## directpv
### 1.install directpv kubectl plugin
```shell
kubectl krew update
kubectl krew install directpv
```
### 2.generate resources.yaml
```shell
kubectl directpv install -o yaml > resources.yaml
```
### 3.replace the resouces.yaml in the director directpv/templates