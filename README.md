# Docker Node MongoDB Example

> Simple example of a dockerized Node/Mongo app

## Quick Start

```bash
# Run in Docker
docker-compose up
# use -d flag to run in background

# Tear down
docker-compose down

# To be able to edit files, add volume to compose file
volumes: ['./:/usr/src/app']

# To re-build
docker-compose build
```
## kubectl commands
```
kubectl status
kubectl version
kubectl get nodes
kubectl get deployment
kubectl get endpoints
kubectl get pods
kubectl get services
kubectl apply -f services.yaml
kubectl apply -f deployment.yaml
kubectl logs node-mongo-deployment-5bff5cc488-4wmq2
```
