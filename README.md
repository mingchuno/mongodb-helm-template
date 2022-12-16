# ...

```
helm repo add bitnami https://charts.bitnami.com/bitnami
helm template -f values.yaml my-mongodb bitnami/mongodb > mongo.yaml
```