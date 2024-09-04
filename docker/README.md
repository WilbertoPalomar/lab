# This lab covers both Docker and Docker Compose

### docker pull python:3.8-slim
### docker run -v "/Users/bert/Desktop/lab/docker/docker-main/lessons/01-starter-code:/src/app/" python:3.8-slim python /src/app/python-app.py
### docker images
### docker ps
### docker ps -a
### docker rm <container_id>
### docker image rm <image_id>
### docker build -t flask-application:0.0.1 .
### docker run flask-application:0.0.1
### docker system prune -a