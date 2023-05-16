## Introduction: 
In this lab we will run an alpine container using an image in docker hub.

We will discuss in more details “images” and “docker hubs” all you need to know now is that docker hub is a repo that includes images; 
and we use images to run a container. 

## Steps:
---
1-  run the official "hello-world" image, which is a simple image that prints "Hello, World!" to the console.

-      docker run hello-world

2- list all of the running Docker containers.

-       docker ps

3- list all of the Docker containers, including those that are not running.

-      docker ps -a

4- remove the specified Docker container.

-      docker rm container_id

5- list all of the Docker images that are currently available on your system.

-      docker images ls

6- download the "alpine" image from Docker Hub.

-      docker pull alpine

7- start a new Docker container from the "alpine" image and attach your terminal to it.

-      docker run -it alpine /bin/sh

8- list all of the running Docker containers.

-      docker ps

9- list all of the Docker containers, including those that are not running.

-      docker ps -a

10- stop the specified Docker container.

-       docker stop container_id

11- start the specified Docker container.

-       docker start container_id

12- start a new Docker container from the "httpd" image and expose port 80 on the host machine.

-       docker run -d --name apache -p 80:80 httpd

13- list all of the running Docker containers.

-       docker ps

14- curl the specified host and port.

-      curl http://host_ip:port

15- get the details of the specified Docker container.

-       docker inspect docker_id


-       curlss http://container_ip:port

##### Note:-

This command will curl the specified container and port using SSL.
