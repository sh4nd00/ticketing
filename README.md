--once microservice created first create image and push with

docker build -t sh4nd00/expiration .


kubectl create secret generic jwt-secret --from-literal=JWT_KEY=asdf


---
to configure nat-test
kubectl get pods  //to get nats pod name
kubectl port-forward nats-depl-5f79c88877-8ggsv 4222:4222
