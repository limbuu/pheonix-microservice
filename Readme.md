# Pheonix

`Pheonix` is a pet project for experimenting different frontiers of micoservice architecture and also get hands on experience with different tools particulary needed to build microservices. 

Another goal of this project is to test the scalibility of the services in response to changing demand/load/traffic. Also, to testify the latency or the speed of the microservice application in comparison to monolith application.   
 
## Architecture :
The microservice application we build her as a experiment has following architecture:
![alt text](https://github.com/limbuu/pheonix-microservice/blob/main/images/architecture.webp)

## Tools Used :
* RabbitMq/Kafka
* Redis
* Mysql
* Mongodb
* API Gateway
* Oauth
* Minikube
* Skaffold
* Prometheus
* Grafana
* Postman

### Prerequsites SetUp
* minikube: `Minikube` is a tool that creates a single node(Virtual Machine) Kubernetes cluster on your computer using VirtualBox or Docker. To install minikube follow this [link.](https://minikube.sigs.k8s.io/docs/start/)
* kubectl: `kubectl` is CLI tool that can be used to deploy applications, inspect and manage cluster resources and view logs. To installl `kubectl` follow this [link.](https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/)
* skaffold: `Skaffold` is a CLI tool that facilates the continuous development and deployment of kubernetes native-applications. It also handles the workflow for building, pushing and deploying applications and provide building blocks for creating CI/CD pipelines for local as well as remote Kubernetes cluster. To install `skaffold` follow this [link.](https://skaffold.dev/docs/install/)



