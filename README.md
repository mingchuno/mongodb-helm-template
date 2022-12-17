# ...

```
helm repo add bitnami https://charts.bitnami.com/bitnami
helm template -f values.yaml my-mongodb bitnami/mongodb > mongo.yaml
helm upgrade --install -f values.yaml mongodb bitnami/mongodb --create-namespace --namespace mongodb-ns
```