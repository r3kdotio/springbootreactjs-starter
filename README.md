# Description
CoreUI React.js + Spring boot

## Docker
### Build
mvn clean package docker:build

### Pull
docker pull r3kdotio/springbootreactjs-starter

## Run
docker run -p 8080:8080 r3kdotio/springbootreactjs-starter

## Kubernetes
kubectl create -f springbootreactjs-starter-deployment.yaml
kubectl expose deployment springbootreactjs-starter-deployment


