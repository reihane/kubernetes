
## managing
### pre command:
1- kubectl api-resources (view resources)
2- kubectl get namespaces 
3- kubectl get nodes

###  pod:
1- kubectl run nginx --image=nginx
2- kubectl get pod
3- kubectl explain pod.metadata.labels
4- kubectl create namespace dev
5- kubectl run nginx --image=nginx -n dev
6- kubectl  delete pod -n dev nginx
7- kubectl logs -f -n dev nginx (if it's not working mean pod not completly up and stay in running,initing ,....)