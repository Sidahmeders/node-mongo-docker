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
   63  kubectl status
   64  kubectl version
   65  kubectl get nodes
   66  kubectl get deployment
  117  kubectl get endpoints
  133  kubectl get pods
  134  kubectl get services
  135  kubectl apply -f services.yaml
  138  kubectl apply -f deployment.yaml
  142  kubectl logs node-mongo-deployment-5bff5cc488-4wmq2

  
