
```bash
cd helm-operator
operator-sdk init --plugins=helm --domain=example.com
```

```bash
helm create app
```

```bash
cd helm-operator
operator-sdk create api --group=example --version=v1 --kind=VisitorsApp 
```

