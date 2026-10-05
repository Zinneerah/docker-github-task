# DevOps Docker Task

## Student Information

Name: Zinneerah Imran  
Student ID: YOUR_STUDENT_ID  
Course: DevOps

## Application Description

This is a simple web application developed as part of the DevOps task.
The application displays student information and a message confirming
that the application is running inside a Docker container.

## Technologies Used

- HTML
- CSS
- JavaScript
- Git
- GitHub
- Docker
- Docker Hub
- Nginx

## Dockerfile Explanation

### FROM nginx:alpine

Uses the lightweight Nginx Alpine image as the base image.

### COPY . /usr/share/nginx/html

Copies the application files into the Nginx web server directory.

### EXPOSE 80

Documents that the application uses port 80 inside the container.

## Docker Commands

### Build the image

docker build -t docker-github-task:v1 .

### Run the container

docker run -d -p 3000:80 --name devops-task zinneerah/devops-task:v1

### Tag the image

docker tag docker-github-task:v1 zinneerah/devops-task:v1

### Push the image

docker push zinneerah/devops-task:v1

### Pull the image

docker pull zinneerah/devops-task:v1

## Docker Hub

Docker Hub Repository:

https://hub.docker.com/r/zinneerah/devops-task

## How to Run

docker pull zinneerah/devops-task:v1

docker run -d -p 3000:80 --name devops-task zinneerah/devops-task:v1

Open the application in a browser:

http://localhost:3000

## Screenshots

1. GitHub repository
2. Dockerfile
3. Docker image
4. Running container
5. Application in browser
6. Docker Hub repository
7. Docker pull