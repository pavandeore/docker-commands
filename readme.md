
Problem: 

dependency don't work well together 
also you don't know which version is compatible with which one 

things works on 1 machine but doesn't work on others machine

starting development easier and fast instead of spending time on configuring project


Solution:

docker  (containerization of things)


Container - you can share this thing, it works on host OS
VM - have their own guest OS



**Images**:  a template used to build a container 

**Containers**: run-time instance of docker image

**Docker file**: contains the commands required to assemble an image

**Docker Hub**: place to host your images and share  (Public)

**Daemon**: a process docker'd listens to events and managers, images, containers, networks, volumes

**Registry**: Stateless highly scalable server side app that stores and let s you distribute docker images  (Private)



**Docker compose** - start and stop service on one machine 

**Swarm** - start and stop services across multiple (like a Kubernetes)



**COMMANDS**


docker -v

docker version --format '{{json .}}'

docker info (information about servers)

docker pull redis  (by default latest version)

docker pull ubuntu:20.04

docker image ls   OR    docker images

docker run redis  (start container from image)

docker ps (list of container running)

docker ps -a  (list of all running or stopped)

docker run -it redis  (interactive)

docker run -d redis  (in the backround)

docker run -it -d redis

docker run -it --name=pawan-redis -d redis  (change name)





