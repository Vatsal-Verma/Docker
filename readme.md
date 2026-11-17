# Docker 

### what is docker ?

Docker is a platform that allows you to package an application along with all its dependencies into a container so that it can run consistently on any machine.

in simple words, Docker is a containerization application which was developed to make the code from "it works only on my machine" -> "it also works on every other machine"

### what is docker container ?

A Docker container is an isolated environment in which your application runs along with everything it needs to work. 
In simple words, it a single unit which contains your code, environments and the dependencies to run that piece of code. 


<img width="911" height="462" alt="image" src="https://github.com/user-attachments/assets/f30afdff-21f5-43a3-a01f-895d1d38eaa4" />


- Dockerfile: Instructions describing what to install and configure.
- Docker Image: The packaged template created using those instructions.
- Docker Container: An instance of that image executing your application.

### Docker Image
A Docker Image contains everything needed to create and start an application inside a Docker container. It acts as a packaged template that Docker uses to create containers.

in simple words, instruction needed to create the docker container. 
