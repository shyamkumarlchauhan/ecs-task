# ecs-task

Poc for using ECS 
This repo contains a demonstration setup of an ECS cluster using terraform as IaC .
Briefly the below resources are bring created with the terraform script.

1. Virtual private cloud (VPC): I want to have our cluster inside a VPC because I want to take over networking and security in my infrastructure.

2. Application Load Balancer: It redirects and balances the traffic to my ECS cluster.

3. Public and private subnets.

4. ECS: A cluster based on EC2 instances. Here I will create tasks and services to deploy our containers.

5. Auto Scaling group: This ECS cluster needs to scale up and down.

6. Amazon CloudWatch: This enables us to store and show Docker container logs. I’ll also use it to create alerts that warn of CPU and memory leaks. 

