# spring-boot-docker
Dockerize Spring Boot Application

Dockerization::

1.creating a Dockerfile
2.creating an image using below command from command prompt
  cmd>docker build -t spring-boot-docker.jar .
3.check the image 
  cmd>docker image ls
4. run the image in a container
   cmd>docker run -p 9090:8080 spring-boot-docker.jar
5. login to docker hub
   cmd>docker login
6. create a tag for the image
   cmd>docker tag spring-boot-docker.jar dockerhubId/spring-boot-docker.jar
7.push it into docker hub
  cmd>docker push dockerhubId/spring-boot-docker.jar
8.we can pull image from docker hub
   docker pull dockerhubId/spring-boot-docker.jar






