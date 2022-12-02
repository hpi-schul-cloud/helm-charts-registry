# Helm Chart Registry

[Helm](https://helm.sh) repo for different charts related or used by dbildungscloud which can be installed on [Kubernetes](https://kubernetes.io)

> :warning: **The Helm Charts are not maintained in this repository**: They are merely collected and published!

### Add Helm repository

To make the helm charts available run:

```bash
helm repo add dbildungscloud https://hpi-schul-cloud.github.io/helm-charts-registry/
helm repo update
```

### Helm Charts

* [edusharing-crawler](https://github.com/hpi-schul-cloud/oeh-search-etl)

  ```bash
  helm install my-release dbildungscloud/edusharing-crawler
  ```
 