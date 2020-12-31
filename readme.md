`
docker build -t kub-first-app:1 .
`

### push image

`
kubectl create deployment first-deployment --image=aybjax/kub-first-app
`
