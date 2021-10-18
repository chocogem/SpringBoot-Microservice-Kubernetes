# SpringBoot Microservice Kubernetes

This project is example Spring boot Microservice Project for deploy on Kubernetes.

The project contains deployment files of 

-eureka-service

-configuration-service

-claim-service

-policy-service

-customer-service  

-mongoDB



# Getting Started 

How to test project.

1.Download Docker desktop https://www.docker.com/products/docker-desktop and Install it.

2.Enable Kubernetes on Docker desktop(Can use other).

3.Build Image and push to Image Registry use docker command on Dockerfile.yml(I used Docker Hub https://hub.docker.com/).

Example.

#build image
docker build -t chocogem/demo-kube-eureka:0.1 .

#push image
docker push chocogem/demo-kube-eureka:0.


4.Deploy service to kubernetes use kubectl command on deployment.yml

Example.

#deploy

kubectl apply -f deployment.yml 

kubectl apply -f mongodb-deployment.yml

#delete deployment

kubectl delete -f deployment.yml



## Built With

* Intelij 2020.1.1
* Maven
* Java
* Spring boot
* MongoDb
* Eureka
* Spring cloud
* Docker
* Kubernetes


## Authors

* **Chocogem** - *Initial work* - [chocogem](https://github.com/chocogem)

