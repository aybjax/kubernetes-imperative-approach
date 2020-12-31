`
docker build -t kub-first-app:1 .
`

### push image


# create pod with given image
`
kubectl create deployment first-deployment --image=aybjax/kub-first-app
`

# service: expose pod to outside using loadbalancer