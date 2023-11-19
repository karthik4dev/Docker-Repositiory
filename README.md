# Docker-Repositiory
This repository is created to learn Docker Automated build 

## To run The Docker File please refer the script . The main purpose of the repository is build the docker automated build 

### Build the image.
docker build -t my-java-docker .


### Run the image
docker run -itd --name my-java-docker-container my-java-docker:latest

### Review the logs to see how the container is running. You can get it by executing $docker ps -a
docker logs -ft <container-id>
