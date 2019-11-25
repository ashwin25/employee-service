# How to run this project

# Docker command to build image

docker build -t employee-service .

# To run docker image

docker run -p 5000:8080 employee-service

# To list all images

docker images

# To find current running docker process

docker ps

# To stop a container

docker stop <container-id obtained from docker ps>

# To remove an image

docker rmi <image id obtained from docker ps>