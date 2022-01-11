# sf_kubernetes

Task 7 Terraform and Kubernetes of orkestration 

main.tf, user-data.txt files for Terraform
nginx-app.yaml file for deployment into Kubernetes

It command of Access to nginx app from Kubernetes cluster
kubectl port-forward --address 0.0.0.0 deployment/my-nginx 8888:80
