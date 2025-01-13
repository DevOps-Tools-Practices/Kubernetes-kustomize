# Kubernetes-kustomize
Basic example to understand kustomize 

## Execution

1. Move to this Directory demo-app/kustomize

```
cd demo-app/kustomize
```

2. Run apply command:
```
kubectl apply -k overlays/staging
```

3. Verification: You can verify if the deployment was successful:

```
kubectl get deployment nginx-deployment
kubectl get pods -l app=nginx
```
