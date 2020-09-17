### Getting started

```sh
npm run dev
```

### Building Docker Image

```sh
minikube start
eval $(minikube docker-env)

cd next_client
docker build -t nuthanc/next_client .
docker run -p 3000:3000 nuthanc/next_client
http://minikube_ip:3000
```