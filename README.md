# sci.abaplint.app
sci.abaplint.app Helm Chart

```
helm install -f sci/values.yaml --namespace sci --create-namespace sci sci/

helm upgrade -f sci/values.yaml --namespace sci sci sci/

helm template -f sci/values.yaml --output-dir sci-template/ sci/

kubectl logs sci-x6xz6 -n sci
```
