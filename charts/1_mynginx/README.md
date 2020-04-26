### How to run

## Thi is very simple helm chart, Its not parametrized.
```text
helm ls
helm install --name XXX .
helm delete --purge XXX
helm upgrade XXX .
helm rollback XXX 1
helm upgrade XXX . --set service.type=NodePort
```