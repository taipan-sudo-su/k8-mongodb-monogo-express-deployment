# k8-mongodb-monogo-express-deployment
## Prerequisites

1. **Kubernetes Cluster**: Ensure you have a running Kubernetes cluster. You can use Minikube for local development.
2. **kubectl**: Ensure `kubectl` is installed and configured to interact with your Kubernetes cluster.
3. **Docker**: Ensure Docker is installed and running.

   steps to deploy mongodb and mongo express in local machine 
   
~~~
kuvectl apply -f mongo-secret.yaml
kubectl apply -f mongo-deployment.yaml
kubectl apply -f mongo-service.yaml
kubectl apply -f mongo-express-cm.yaml 
kubectl apply -f mongo-express-deployment.yaml
kubectl apply -f mongo-express-service.yaml
~~~
