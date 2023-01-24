# Kubernetes Assignment

Please follow these steps in order to deploy.

```shell
# build docker image
docker build -t natchanon/video-streaming .

# deploy kubernetes cluster
kubectl create -f deployment.yml
```

To check deployment status
```
minikube dashboard --url
```

Create tunnel for checking running application
```
minikube service video-streaming-service
```