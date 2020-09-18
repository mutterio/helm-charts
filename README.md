![publish-chart](https://github.com/mutterio/helm-charts/workflows/publish-chart/badge.svg)

# mutter.io helm-charts

index can be found [here](https://mutterio.github.io/helm-charts/index.yaml)

Adding the mutterio repo to your helm
```bash
helm repo add mutterio https://mutterio.github.io/helm-charts
helm install localstack mutterio/localstack
```

## localstack-helm
A Helm chart for deploying Localstack on Kubernetes

```bash
helm install localstack mutterio/localstack
```