# Static-website-in-K8s
Deploying our custom website inside k8s using k8s object "deployment" and "service" 

I created my own docker image

After  creation, I used my docker images to deploy inside k8s using service and deploy.

Mainly I tested this demo using "Minkube", You can try this anywhere

Commands used for me in Minikube

Minikube start- For starting minikube in a local machine

Minikube status - For checking the status of Minkube

kubectl get pods - To list No pods in the cluster

kubectl get deploy - To list the deployment

kubectl get service - To list the service

kubectl create -f <deployment-file-name> - Useful for creation of deployment file

kubectl create -f <service-file-name> - Useful for creation of service file

Minikube service <service-name> - Useful for accessing service inside the cluster 

