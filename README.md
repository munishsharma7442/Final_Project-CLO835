# Final_Project-CLO835
Final Project: Deployment of 3-tiered web application to managed K8s cluster on Amazon EKS.


k apply -f secret-data.yaml -n final
k apply -f mysql-deployment.yaml -n final
k apply -f mysql-service.yaml -n final
k apply -f webapp-deployment.yaml -n final
k apply -f webapp-service.yaml -n final