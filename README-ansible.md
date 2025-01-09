
```bash
cd ansible-operator
operator-sdk init --plugins=ansible --domain=example.com
```

需要k8s环境
```bash
cd ansible-operator
operator-sdk create api --group=example --version=v1 --kind=VisitorsApp 
```

