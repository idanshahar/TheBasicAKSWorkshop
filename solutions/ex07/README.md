```
kubectl create configmap example-app-data --from-env-file env.txt

kubectl apply -f example-app-deployment.yaml

kubectl apply -f example-app-service.yaml
```

