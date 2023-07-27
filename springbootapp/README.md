# talentplus-msapp
Code base for the deployment of microservice application given by Talentplus as a take-home project for Senior Devops Engineer position

# Tech Stack Used For Successful Deployment Of The MicroService Application
AWS
AmazonEKS
Jenkins
Docker
Kubernetes
Anisble
Helm
Springboot

# Breif Explanation on TechStack
Aws was used to launch instances which served as a remote server for installation of the AmazonEKS, Jenkins, Docker, Ansible, Helm.
AmazonEKS was used ton set of Kubernetes cluster with two worker nodes
Docker: This is used to manage containers and images in instances from AWS
Kubernetes: This was used to manage and automate the deployment of the microservice containerized application
Ansible served as an IaC for remote servers where are the Jenkins master and slave and also two worker nodes in Eks cluster.
Helm used to package the microservice application and set it up on EKS Cluster
Version Control for Jenkins CI/CD pipeline.
