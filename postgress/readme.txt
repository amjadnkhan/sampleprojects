1- Config Maps for PostgreSQL Configurations. First create map config that can be used for deployement
kubectl create -f postgres-configmap.yaml 
2- Create persistant volume
kubectl create -f postgres-storage.yaml
3- Postgris deployment
kubectl create -f postgres-deployment.yaml 