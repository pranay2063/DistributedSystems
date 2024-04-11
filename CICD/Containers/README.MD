
## Docker 

A container is a unit of software that encapsulates everything needed to build, ship, and run applications.  

Containers lower deployment time and costs, improve utilization, automate processes, and support next-gen applications (microservices). Major container vendors include Docker, Podman, LXC, and Vagrant. 

Docker is an open platform used for developing, shipping, and running applications as containers. 

Docker containers are not a good fit for applications based on monolithic architecture or applications that require high performance or security. 

Docker architecture consists of the Docker client, the Docker host, and the container registry. 

The Docker host contains objects such as the Dockerfiles, images, containers, networks, storage volumes, and other objects, such as plugins and add-ons. 

Docker uses networks to isolate container communications. 

Docker uses volumes and binds mounts to persist data even after a container stops running. 

Plugins, such as storage plugins, provide the ability to connect to external storage platforms. 

Cheat Sheet: Docker CLI

Command	Description
curl localhost	Pings the application. <br>
docker build	Builds an image from a Dockerfile. <br>
docker build . -t	Builds the image and tags the image id. <br>
docker CLI	Start the Docker command line interface. <br>
docker container rm	Removes a container. <br>
docker images	Lists the images. <br>
docker ps	Lists the containers. <br>
docker ps -a	Lists the containers that ran and exited successfully. <br>
docker pull	Pulls the latest image or repository from a registry. <br>
docker push	Pushes an image or a repository to a registry. <br>
docker run	Runs a command in a new container. <br>
docker run -p	Runs the container by publishing the ports. <br>
docker stop	Stops one or more running containers. <br>
docker stop $(docker ps -q)	Stops all running containers. <br>
docker tag	Creates a tag for a target image that refers to a source image. <br>
docker –version	Displays the version of the Docker CLI. <br>
exit	Closes the terminal session. <br>
ls	Lists the contents of this directory to see the artifacts. <br>
