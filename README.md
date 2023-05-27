
```bash
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm repo update
```

```bash
helm install prometheus prometheus-community/kube-prometheus-stack
```

```bash
helm uninstall prometheus prometheus-community/kube-prometheus-stack
```