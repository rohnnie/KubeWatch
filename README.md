# KubeWatch

## Objective

Deploying a web application on Kubernetes using Docker containers. The process includes containerizing the application, creating a persistent volume, pushing the image to Docker Hub, and deploying the container on both Minikube and AWS EKS. We will also explore various Kubernetes features such as replication controllers, health monitoring, rolling updates, and alerting.

## Prerequisites

Before you start this assignment, ensure you have the following:

- Basic understanding of Docker and Kubernetes
- Docker installed on your computer
- Minikube and Kubectl installed on your computer
- An AWS account
- DockerHub account

## Part 1: Creating an Application

- Create a simple To-Do web application using Flask and MongoDB.
- Source code for the application can be accessed here.

## Part 2: Containerizing the Application on Docker

### 1. Install Docker:
 - Download and install Docker from the official website.

### 2. Create Docker Containers:
 - One container for the Flask app and one for persisting data in MongoDB.

### 3. Write a Dockerfile:
 - Instructions to build the Docker image for the Flask application.

### 4. Build Docker Image:
 - Use the Docker CLI to build the image:

### 5. Test Application Locally:
 - Write a docker-compose.yml file.

### 6. Push Docker Image to Docker Hub:
 - Push the image.

## Part 3: Deploying the Application on Minikube

### 1. Install Minikube:
 - Follow the [official documentation](https://minikube.sigs.k8s.io/docs/start/).

### 2. Start Minikube:
 - Use the CLI to start Minikube:
   ```sh
   minikube start

### 3. Create Pods:
 - One for the Flask app and one for MongoDB.

### 4. Create Kubernetes Deployment

### 5. Expose Deployment

### 6. Test Application

## Part 4: Deploying the Application on AWS EKS

## Part 5: Replication Controller

## Part 6: Rolling Update Strategy

## Part 7: Health Monitoring

## Part 8: Alerting
