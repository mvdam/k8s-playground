Start

```sh
kubectl apply -f mongo-secret.yaml
kubectl apply -f mongo.yaml

kubectl apply -f mongo-configmap.yaml
kubectl apply -f mongo-express.yaml

kubectl delete -f mongo-express.yaml
```

Important notes:

- Secrets and ConfigMaps must be created before Deployment
- values in Secret must be base64 encoded
- `minikube tunnel` / `minikube service <externalServiceName>`
