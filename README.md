# kubernewhatnow
Getting started with Kubernetes


## Some basic commands 
Viewing resources in a namespace
```
kubectl get deployments --namespace <namespace>
```

Describing the resources, or basically getting more information of app
```
kubectl describe deployment <app_resource> --namespace <namespace>
```

Creating a resource
```
kubectl apply -f <yaml file>
```

## Some important facts

- kube-system is not a user created namespace. It is provided by the cluster

- The apply command is a declarative command, not imperative, telling kubernetes to apply the necessary changes based on the yaml file requirements

