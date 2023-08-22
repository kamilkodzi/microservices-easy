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

# Good to know k8s's deploymentscommands
`kubectl get deployments`

`kubectl describe deployment [depl name]`

`kubectl apply -f [config file name]`

`kubectl delete deployment [depl_name]`

`kubectl rollout restart deployment [depl_name]`


`skaffold dev - to start cluster`