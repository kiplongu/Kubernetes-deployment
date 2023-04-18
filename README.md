# Kubernetes-deployment

# Important commands

kubectl create -f voting-app-pod.yaml -- creating the internal resource ie ClusterIP
kubectl create -f voting-app-service.yaml -- creating external resource eg NodePort

kubectl create -f redis-pod.yaml -- creating the internal resource ie ClusterIP
kubectl create -f redis-service.yaml -- creating external resource eg NodePort

kubectl create -f postgres-pod.yaml -- creating the internal resource ie ClusterIP
kubectl create -f postgres-service.yaml -- creating external resource eg NodePort

kubectl create -f result-app-pod.yaml -- creating the internal resource ie ClusterIP
kubectl create -f result-app-service.yaml -- creating external resource eg NodePort

# Checking pods and services
kubectl get pods, svc

# To get the url to test if it is accessible via browser
minikube service voting-service --url--gets you the url


