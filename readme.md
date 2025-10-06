# Container Champion: CI/CD for Containerized Web Application on AWS ECS
A simple Python Flask web app containerized using Docker and prepared for deployment on AWS ECS.

## Run Locally
1. Build the Docker image:
   docker build -t container-champion .
2. Run the container:
   docker run -p 80:80 container-champion
