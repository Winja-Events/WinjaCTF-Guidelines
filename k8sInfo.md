Steps for converting the docker-compose.yaml file into k8s files
- Install the kompose using any of the method mentioned in the link below  
https://kompose.io/installation/
- Run the below command by specifying the docker compose file  
`kompose convert -f docker-compose.yaml`
- kompose will create the deployment and service files
- Verify the details in the generated k8s files
- Set up the k8s environment by using any of the k8s provider like minikube, microk8s, etc
- Run and interact with the k8s env using kubectl

References:
- https://kubernetes.io/docs/tasks/tools/
- https://kompose.io/
- https://microk8s.io/
- https://minikube.sigs.k8s.io/docs/start/

