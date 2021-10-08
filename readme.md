# Get started with k8s

### Check that env is ready
    sudo systemctl start docker
    minikube start
    kubectl get pods

### Apply the deployment
    kubectl apply -f deployment.yaml
    kubectl get pod
    kubectl describe pod

### Set the networking
    kubectl apply -f service.yaml
    kubectl get service
    kubectl describe service
    kubectl get pod -o wide

### Enjoy
    minikube service nginx-service
