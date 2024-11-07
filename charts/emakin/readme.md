# Emakin Helm Charts

# install

```bash
helm install hello .\
    --set host=mycompany.com \
    --create-namespace \
    --namespace emakin-ns
```

# uninstall

```bash
helm uninstall hello --namespace emakin-ns
```
