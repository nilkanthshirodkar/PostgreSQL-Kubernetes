# PostgreSQL-Kubernetes
Deploy PostgreSQL on Kubernetes => Postgres Docker Image, Config Maps for storing Postgres configurations, Persistent Storage Volume, PostgreSQL Deployment, PostgreSQL Service


$ kubectl create -f postgres-configmap.yaml 

$ kubectl create -f postgres-storage.yaml 

$ kubectl create -f postgres-deployment.yaml 

$ kubectl create -f postgres-service.yaml 

$ kubectl get svc postgres

kubectl get pods -- This command will give all the pods

Now you will have to connect your Pod using command

kubectl exec -it <podname> -- /bin/bash

