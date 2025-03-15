# knote-java

https://github.com/learnk8s/knote-java


```bash

kubectl create namespace my-knote

# at root folder
kubectl apply -f kube


kubectl port-forward service/knote 8080:80 -n my-knote
# then u can try it



# clean up

kubectl delete all --all -n my-knote

```
