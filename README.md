# Good to know docker commands
`docker build -t kamilkodzi/posts .`

`docker run [image id or tag]`

`docker run -t [image id or tag] [cmd]`

`dockre ps`

`docker exec -it [container id] [cmd]`

`docker logs [container id]`


# Good to know k8s commands
`kubectl get pods`

`kubectl exec -it [pod_name] [cmd]`

`kubectl logs [pod_name]`

`kubectl delete pod [pod_name]`

`kubectl apply -f [config file name]`

`kubectl describe pod [pod_name]`

# Good to know k8s's services commands
`kubectl get namespace`

`kubectl get services`

`kubectl get services -n ingress-nginx`

# Good to know k8s's deployments commands
`kubectl get deployments`

`kubectl describe deployment [depl name]`

`kubectl apply -f [config file name]`

`kubectl delete deployment [depl_name]`

`kubectl rollout restart deployment [depl_name]`

`skaffold dev - to start cluster`

# Creating secrets for development purposes:

`kubectl create secret generic jwt-secret --from-literal=JWT_KEY=qwerty`

`kubectl get secrets`