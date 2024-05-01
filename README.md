# Describtion
### The Project Contaion 2 Deployment and 2 service and 1 secret and 1 ConfigMap and I used Minikube Cluster
#### one Deployment for The Front-End application Mongo Express with Nodeport Service  and  one Deployment for Back-end Application Monogo Database with ClusterIP service 
#### one secret to Put the username and Password of the Database
#### one ConfigMap store and manage configuration data
<div>
<img src="https://github.com/AhmedYasserMohamed/Complete-Frontend-Backend-Application-Deployment-using-Kubernetes-Components/assets/166765792/0a0afbec-2845-4352-9e25-76c8b278b9df">
<img src="https://github.com/AhmedYasserMohamed/Complete-Frontend-Backend-Application-Deployment-using-Kubernetes-Components/assets/166765792/12ed5d17-8fda-4905-a48f-f2f2640d614e">
</div>

```
minikube start

kubectl apply -f mongodb_secrets

kubectl apply -f mongo_db

kubectl apply -f mongo-cofigmap

kubectl apply -f mongo-express

minikube service mongo-express-service
```



<div>
<img src="https://github.com/AhmedYasserMohamed/Complete-Frontend-Backend-Application-Deployment-using-Kubernetes-Components/assets/166765792/7f0831cb-150e-4a89-99ac-0bf52282e9ce">
<img src="https://github.com/AhmedYasserMohamed/Complete-Frontend-Backend-Application-Deployment-using-Kubernetes-Components/assets/166765792/08c75afc-80eb-41f3-9e97-b4a8dabde9ab">
<img src="https://github.com/AhmedYasserMohamed/Complete-Frontend-Backend-Application-Deployment-using-Kubernetes-Components/assets/166765792/17272c9f-bb30-4bb1-af34-334531479a70">
</div>
