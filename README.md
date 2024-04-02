# Dockerizing-Flask-App
Containerising a Python Flask Application with Docker

In this project I created the following: 

- A Python Flask application for my CV web page
- Containerized the app with Docker
- Pushed the container image it to DockerHub
- Tested the containerized application

My blog for this project is here: https://www.linkedin.com/pulse/build-deploy-containerise-python-flask-web-app-docker-shai-shaunai--zfyze/

Following from the inital Docker Image build, I utilised AWS services:

- ECR - Elastic Container Registry (fully managed Docker container registry that makes it easy to store, share, and deploy container images)
- ECS -Elastic Container Service (fully managed container orchestration service that simplifies your deployment, management, and scaling of containerized applications) 
- Fargate (serverless compute engine for containers) to deploy the containerised application

  Using these services enabled the deployment of the Docker container to ECS using Fargate, and the application can be run in a scalable and managed environment.
