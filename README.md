# Exploring Minikube

**Q. What is Minikube?**

Minikube is an open-source tool that allows you to run a single-node Kubernetes cluster on your local machine. It is primarily used by developers for learning, testing, and day-to-day development without needing a full-scale cloud-based cluster. 

While running our `webapp-service` 

**Q. What are `namespaces`? How to see namespaces of all the pods inside the node?**

Run
```zsh
kubectl get pods --all-namespaces
```

This outputs:


We see `kube-proxy` also inside `kube-system` namespace along with the `control-panel` components. But, **Q. Does Minikube have no 'kubelet'? If it does, Where is `kubelet`?**