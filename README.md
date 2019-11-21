kubectl apply -f pod-nginx.yaml

kubectl get pods –o wide

docker ps | grep hello-nginx


curl 10.1.155.146


kubectl logs hello-nginx


docker rm -f 6b43c3fd5ee3


kubectl get pods –o wide


kubectl delete pods hello-nginx
kubectl delete –f pod-nginx.yaml



# hands-on
