Install Kind cluster
kind create cluster --name media --config config.yaml --image kindest/node:v1.19.0

Install Docker
https://docs.docker.com/engine/install/ubuntu/

Install Kubectl
https://kubernetes.io/docs/tasks/tools/install-kubectl/

Install ArgoCD
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
