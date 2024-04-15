# Redis Deployment using Kubernetes
A simple deployment of Redis using Kubernetes for development and testing purposes.

## Prerequisites
- [`kubectl` CLI](https://kubernetes.io/docs/tasks/tools/)
- Local Kubernetes cluster
  - [Docker Desktop Kubernetes](https://docs.docker.com/desktop/kubernetes/)
  - [Minikube](https://minikube.sigs.k8s.io/docs/start/)

## Usage
- `./stack pvc` # Deploy persistent volume claim
- `./stack up` # Deploy Redis
- `./stack logs` # See logs
- `./stack rcli` # Connect to the database
