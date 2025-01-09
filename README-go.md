
```bash
cd go-operator
operator-sdk init --domain=example.com
```

需要k8s环境
```bash
cd go-operator
operator-sdk create api --group=example --version=v1 --kind=VisitorsApp 
```
