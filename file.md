## DOCKER COMMANDS

1. This command is used to get the currently installed version of docker
~~~
 # docker –version
~~~
2. This command is used to pull images from the docker repository(hub.docker.com)
~~~
# docker pull <image name>
~~~
3. This command is used to create a container from an image
~~~
# docker run -it -d <image name>
~~~
4. This command is used to list the running containers
~~~
# docker ps
~~~
5. This command is used to show all the running and exited containers
~~~
# docker ps -a
~~~
6. This command is used to access the running container
~~~
# docker exec -it <container id> bash
~~~
7. This command stops a running container
~~~
# docker stop 
~~~
8. This command kills the container by stopping its execution immediately. 
~~~
# docker kill <container id>
~~~
9. This command creates a new image of an edited container on the local system
~~~
# docker commit
~~~
10. This command is used to login to the docker hub repository
~~~
# docker login
~~~
11. This command is used to push an image to the docker hub repository
~~~
# docker push <image name>
~~~
12. This command lists all the locally stored docker images
~~~
# docker images
~~~
13. This command is used to delete a stopped container
~~~
# docker rm
~~~
14. This command is used to delete an image from local storage
~~~
# docker rmi <image-id>
~~~
15. This command is used to build an image from a specified docker file
~~~
# docker build <path to docker file>
~~~