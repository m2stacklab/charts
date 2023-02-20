#Go bar microservice: A simple Helm chart

## Foo (Python) microservice

### local helm install

```bash
helm install foo-micro . -f values.foo.yaml
```

### install from repository

```bash
helm install foo-micro m2stacklab/microservice -f values.foo.yaml
```

## Bar (GO) microservice

### local helm install

```bash
helm install bar-micro . -f values.bar.yaml
```

### install from repository

```bash
helm install bar-micro m2stacklab/microservice -f values.bar.yaml
```
