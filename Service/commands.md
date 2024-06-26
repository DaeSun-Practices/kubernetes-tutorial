kubectl create -f deployment.yaml 
kubectl get deployment

kubectl create -f clusterIP.yaml
kubectl get svc
kubectl describe svc clusterip-service
kubectl delete svc clusterip-service


kubectl create -f nodePort.yaml
kubectl get svc