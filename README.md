# Final_Project-CLO835
Final Project: Deployment of 3-tiered web application to managed K8s cluster on Amazon EKS.

<img width="488" alt="image" src="https://user-images.githubusercontent.com/65021757/184523732-a2ac3658-1d79-46f7-8ce2-bb5b01dfbdd3.png">

k apply -f secret-data.yaml -n final
k apply -f mysql-deployment.yaml -n final
k apply -f mysql-service.yaml -n final
k apply -f webapp-deployment.yaml -n final
k apply -f webapp-service.yaml -n final