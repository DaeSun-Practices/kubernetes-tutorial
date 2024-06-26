kubectl run web1 --image=nginx:1.14 --port=80
kubectl get pods
kubectl get pods -o wide
kubectl delete pod web1 private-reg

kubectl describe pod web1 


watch kubectl get pods -o wide
kubectl get pods -o wide --watch



kubectl create -f pod.yaml