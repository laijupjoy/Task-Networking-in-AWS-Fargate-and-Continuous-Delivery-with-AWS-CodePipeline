## Task-Networking-in-AWS-Fargate-and-Continuous-Delivery-with-AWS-CodePipeline

AWS Fargate is a technology that you can use with Amazon ECS to run containers without having to manage
servers or clusters of Amazon EC2 instances. With Fargate, you no longer 
have to provision, configure, or scale clusters of virtual machines to run containers.

Fargate is a Container as a Service (CaaS) technology or Fargate is a Platform as a Service (PaaS)-like layer
on top of ECS that abstracts the infrastructure which enables users to focus on the desired state of the application.
We don't have to worry about where will deploy containers, or how will manage and scale them.

This project shows how to deploy a machine learning web application on AWS-Fargate with Task Networking and
 Continuous Delivery with AWS CodePipeline
 
## Diagram shows deploy application on ECS using AWS Fargate.

<p align="center">
  <img src="images\diagram.png" alt="workflow"/>
</p>

## Project Tasks:

1. Train and develop a machine learning pipeline for deployment.
2. Build a web app using a Flask framework. It will use the trained ML pipeline to 
   generate predictions on new data points in real-time.
3. Build and push a Docker image onto Amazon Elastic Container Registry.




