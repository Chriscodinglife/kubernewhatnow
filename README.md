# kubernewhatnow
Getting started with Kubernetes and Docker


## Some Kubectl basic commands 
Viewing resources in a namespace
```
kubectl get deployments --namespace <namespace>
```

Describing the resources, or basically getting more information of app
```
kubectl describe deployment <app_resource> --namespace <namespace>
```

Creating a and apply settings to resource
```
kubectl apply -f <yaml file>
```

## Some more kubectl commands

Apply a configuration to a resource
```
kubectl apply
```

Displays clusters defined in the kubeconfig.
```
kubectl config get-clusters
```

Create a resource
```
kubectl create
```

Delete a resource
```
kubectl delete
```

Expose a resource to the internet as a new Kubernetes service
```
kubectl expose
```

Manage the rollout of a resource
```
kubectl rollout
```

List all the pods in the namespace
```
kubectl get pods
```

Create and runs a particular image in a pod
```
kubectl run
```

Prints the client and server version information
```
kubectl version
```

## Some important facts for Kubernetes

- kube-system is not a user created namespace. It is provided by the cluster

- The apply command is a declarative command, not imperative, telling kubernetes to apply the necessary changes based on the yaml file requirements


# Useful info
![container_defs](containers_definitions.png)
