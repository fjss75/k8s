Repository contains different configuration files to be used by a Kubernetes platform.
It requires docker and minikube installed for a local test.

once minikube started, then a container from my dockerhub account can be pulled with next command:
- kubectl run iris --image=fjsoto/iris_model:v2
