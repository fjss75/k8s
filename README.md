Repository contains different configuration files to be used by a Kubernetes platform.
It requires docker and minikube installed for a local test.

some commands I used:
- minikube start
- minikube status
- minikube dashboard
- kubectl get info
- kubectl get nodes
- kubectl apply -f iris-deployment.yaml
- kubectl apply -f iris-service.yaml
- minikube service iris-service
- minikube service iris-service --url
