# Kubectl Commands

- To find all the namspaces inside the node
```zsh
kubectl get pods --all-namespaces
```

- To check the storage provisioner being used in the cluster
```zsh
kubectl get storageclass
```

Output:
```
NAME                 PROVISIONER                RECLAIMPOLICY   VOLUMEBINDINGMODE   ALLOWVOLUMEEXPANSION   AGE
standard (default)   k8s.io/minikube-hostpath   Delete          Immediate           false                  29h
```