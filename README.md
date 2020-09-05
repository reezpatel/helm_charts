### Helm Charts

---

#### Devpunk Helm Chart

##### To update Helm

```
helm lint src/*

helm package src/*

helm repo index --url https://reezpatel.github.io/helm_charts/ .
helm repo index --url https://reezpatel.github.io/helm-charts/ --merge index.yaml .
```

##### To install Chart

```
helm repo add my_helm_chart https://reezpatel.github.io/helm-charts/
```
