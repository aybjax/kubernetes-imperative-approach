`
docker build -t kub-first-app:1 .
`

### push image


# create pod with given image
`
kubectl create deployment first-deployment --image=aybjax/kub-first-app
`

# service: expose pod to outside using loadbalancer

`
kubectl expose deployment first-deployment --port=8080 --type=LoadBalancer
kubectl get services
minikube service first-deployment
`