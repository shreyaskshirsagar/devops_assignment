#DOCKER CMD
#Cmd to build docker image
docker build -t hello_world #this will build docker image locally

#Cmd to run container image
docker run -p 3000:3000 hello_world


#K8S CMD
kubectl apply -f hello_wrd.yaml

# hello-world Helm Chart CMD

A simple Helm chart to deploy a "Hello World" app with configurable replica count.

---

## Prerequisites

- Kubernetes cluster (v1.16+)
- Helm 3+

---

## Installation

Install the chart with the default replica count:

#Cmd for helm chart Installation
helm install hello-world ./hello-world --set replicaCount=3

#Cmd for helm chart upgrade
helm upgrade hello-world ./hello-world --set replicaCount=5

#cmd for uninstalltion
helm uninstall hello-world


#Cmd to build docker image
docker build -t hello_world #this will build docker image locally

#Cmd to run container image
docker run -p 3000:3000 hello_world





# Terraform CMD
Move to terraform terraform directory and execute below cmd

terraform init
terraform plan
terraform apply

After successful infrastructure creation public IP of ec2 instance will get created
