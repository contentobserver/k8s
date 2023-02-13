Basic Helm chart to test the deployment of publicly available sample app hello-world

The installation of this Helm chart results on Kubernetes in:

- Deployment, with a pod (and specified number of replicas)
- Service, exposing the deployed web-app (on port 8080)
- Ingress, providing custom host and domain name based access to the app, via the service
