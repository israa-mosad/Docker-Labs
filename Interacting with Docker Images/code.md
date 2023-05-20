## Introduction: 
Hello there! Now you know what images are. Let’s try to interact with images using some basic commands. 

### Commands Manifesto: 

• Docker pull : to pull an image from docker hub

• Docker push: to push an image to docker hub

• Docker images: lists images

• Docker images –a: show all even intermediate

• Docker images --no-trunc : show full length of ID

• Docker images --filter=reference='****': if I want to filter out the images shown

## Lab Instructions:
1- Pull different versions on alpine image
-         docker pull alpine
-         docker pull alpine:3.14.9
-         docker image ls

• Run 2 containers from alpine image
-       docker run --name container01 alpine
-       docker run --name container02 alpine
-       docker rmi image_id
-       docker rm container01
-       docker rm container02
-       docker rmi image_id
