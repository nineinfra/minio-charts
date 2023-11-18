# Helm Chart for Minio DirectPV

This Helm Chart can be used to install Custom Resource Definitions and the Operator for Minio DirectPV provided by Nineinfra.

## Requirements

- Create a [Kubernetes Cluster](../Readme.md)
- Install [Helm](https://helm.sh/docs/intro/install/)

## Install the Minio Operator

```bash
# From the root of the operator repository
helm repo add nineinfra-charts https://nineinfra.github.io/nineinfra-charts/
helm install minio-directpv nineinfra-charts/minio-directpv
```

## Usage of the CRDs

The usage of this operator and its CRDs is described in the [documentation](https://github.com/nineinfra/metastore-operator/blob/main/README.md).

## Links

https://github.com/nineinfra/minio-charts
