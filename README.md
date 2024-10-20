# Flask + Redis (Kubernetes)

## Steps to deploy

1. Build Docker image and publish to Docker Hub

```bash
cd flask
docker build -t flask-app .
docker tag flask-app:latest zhuravchak/flask-app:latest
docker push zhuravchak/flask-app:latest
```

2. Run Kubernetes cluster

```bash
# TODO
```
