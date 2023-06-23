
# DevSecOps - Kubernetes DevOps & Security

These are the code files from the [DevSecOps course](https://kodekloud.com/courses/devsecops/) hosted on Codecloud.


### Fork and Clone this Repo

### Clone to Desktop and VM

### NodeJS Microservice - Docker Image -

`docker run -p 8787:5000 kittu-85/node-service:v1`

`curl localhost:8787/plus-one/99`
 
### NodeJS Microservice - Kubernetes Deployment -
`kubectl create deploy node-app --image kittu-85/node-service:v1`

`kubectl expose deploy node-app --name node-service --port 5000 --type ClusterIP`

`curl node-service-ip:5000/plusone/99`
