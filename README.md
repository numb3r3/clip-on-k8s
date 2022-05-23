# Helm Charts

This is where I keep my helm charts!

Currently, the available charts are:

- [Clip-on-K8S](./charts/clip-on-k8s/README.md)

## Install a chart

Assuming you have [Helm](https://helm.sh/) installed,

```sh
helm repo add numb3r3 https://numb3r3.github.io/charts/
helm upgrade --cleanup-on-fail --install -n jina-clip-on-k8s --create-namespace my-clip-on-k8s numb3r3/clip-on-k8s
```

For customization options, see the README.md for [each chart](./charts/).