## React App Deployment on Kubernetes

This project demonstrates how to build, deploy, and expose a React application on Kubernetes using Ingress.

**Steps to reproduce-** 

1. Install minikube and setup a cluster.
2. Create a namespace react-app
3. Deployment file is created in k8s directory.
4. Service and Ingress file is created in k8s directory.
5. Run Kustomization.yaml
6. Install nginx ingress controller and enable minikube ingress plugin
7. Add the host in /etc/hosts file
8. Access the application on browser using http://my-react-app.local
