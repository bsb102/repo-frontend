# Kubernetes manifests

## Aplicar recursos

```bash
kubectl apply -f k8s/namespace.yaml
kubectl apply -f k8s/frontend-deployment.yaml -f k8s/frontend-service.yaml -f k8s/hpa-frontend.yaml -n innovatech
```

## Verificar

```bash
kubectl get pods,svc,hpa -n innovatech
```
