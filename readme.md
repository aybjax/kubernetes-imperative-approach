#### create deployment

```
kubectl apply -f=deployment.yaml
```

#### create service

```
kubectl apply -f=service.yml
```

### to get minikube access ( with service name )

```
minikube service second-deployment-service
```


### delete all

```
kubectl delete -f=deployment.yaml,service.yml
```




**IF WANT TO USE SINGLE FILE**

`
kubectl apply -f=master-onefile.yml
`
*and*
`
kubectl delete -f=master-onefile.yml
`