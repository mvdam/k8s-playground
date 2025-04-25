# k8s-playground

Learning k8s &amp; argocd

Dashboard: http://127.0.0.1:53831

```sh
kubectl apply -f ./frontend-1/frontend-1-deployment.yml
kubectl apply -f ./frontend-1/frontend-1-service.yml

# delete
kubectl delete -f ./frontend-1/frontend-1-deployment.yml
kubectl delete -f ./frontend-1/frontend-1-service.yml
```

TODO:

- https://www.youtube.com/watch?v=80Ew_fsV4rM - Ingress
- Istio ???
