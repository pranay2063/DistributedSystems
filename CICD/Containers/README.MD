
## Docker 

A container is a unit of software that encapsulates everything needed to build, ship, and run applications.  

Containers lower deployment time and costs, improve utilization, automate processes, and support next-gen applications (microservices). Major container vendors include Docker, Podman, LXC, and Vagrant. 

Docker is an open platform used for developing, shipping, and running applications as containers. Docker containers are not a good fit for applications based on monolithic architecture or applications that require high performance or security. 

Docker architecture consists of the Docker client, the Docker host, and the container registry. The Docker host contains objects such as the Dockerfiles, images, containers, networks, storage volumes, and other objects, such as plugins and add-ons. 

Docker uses networks to isolate container communications. Docker uses volumes and binds mounts to persist data even after a container stops running. Plugins, such as storage plugins, provide the ability to connect to external storage platforms. 

Cheat Sheet: Docker CLI

| Command  | Description |
| ------------- | ------------- |
| curl  | Pings the application  |
| docker build  | Builds an image from a Dockerfile  |
| docker build . -t | Builds the image and tags the image id |
| docker CLI | Start the Docker command line interface |
| docker container rm | Removes a container |
| docker images | Lists the images |
| docker ps | Lists the containers |
| docker ps -a | Lists the containers that ran and exited successfully |
| docker pull | Pulls the latest image or repository from a registry |
| docker push | Pushes an image or a repository to a registry | 
| docker run | Runs a command in a new container |
| docker run -p	| Runs the container by publishing the ports |
| docker stop	| Stops one or more running containers | 
| docker stop $(docker ps -q)	| Stops all running containers | 
| docker tag | Creates a tag for a target image that refers to a source image | 
| docker –version	| Displays the version of the Docker CLI | 
| exit | Closes the terminal session|
| ls | Lists the contents of this directory to see the artifacts | 

Glossary: Container Basics

| Term	| Definition |
| ------------- | ------------- |
| Client-server architecture	| is a distributed application structure that partitions tasks or workloads between the providers of a resource or service, called servers, and service requesters, called clients. |
| A container	| powered by the containerization engine, is a standard unit of software that encapsulates the application code, runtime, system tools, system libraries, and settings necessary for programmers to efficiently build, ship and run applications.
| Container Registry	| used for the storage and distribution of named container images. While many features can be built on top of a registry, its most basic functions are to store images and retrieve them. | 
| CI/CD | pipelines	A continuous integration and continuous deployment (CI/CD) pipeline is a series of steps that must be performed in order to deliver a new version of software. CI/CD pipelines are a practice focused on improving software delivery throughout the software development life cycle via automation. | 
| Cloud native	| A cloud-native application is a program that is designed for a cloud computing architecture. These applications are run and hosted in the cloud and are designed to capitalize on the inherent characteristics of a cloud computing software delivery model. | 
| Daemon-less	| A container runtime that does not run any specific program (daemon) to create objects, such as images, containers, networks, and volumes. | 
| DevOps | is a set of practices, tools, and a cultural philosophy that automate and integrate the processes between software development and IT teams. | 
| Docker	| An open container platform for developing, shipping and running applications in containers. | 
| A Dockerfile	| is a text document that contains all the commands you would normally execute manually in order to build a Docker image. Docker can build images automatically by reading the instructions from a Dockerfile. | 
| Docker client	| is the primary way that many Docker users interact with Docker. When you use commands such as docker run, the client sends these commands to dockerd, which carries them out. The docker command uses the Docker API. The Docker client can communicate with more than one daemon. | 
| Docker Command Line Interface (CLI)	| The Docker client provides a command line interface (CLI) that allows you to issue build, run, and stop application commands to a Docker daemon. | 
| Docker daemon (dockerd)	| creates and manages Docker objects, such as images, containers, networks, and volumes. | 
| Docker Hub	| is the world's easiest way to create, manage, and deliver your team's container applications. | 
| Docker localhost	| Docker provides a host network which lets containers share your host’s networking stack. This approach means that a localhost in a container resolves to the physical host, instead of the container itself. |
| Docker remote host	| A remote Docker host is a machine, inside or outside our local network which is running a Docker Engine and has ports exposed for querying the Engine API. | 
| Docker networks	| help isolate container communications. |
| Docker plugins	| such as a storage plugin, provides the ability to connect external storage platforms. |
| Docker storage	| uses volumes and bind mounts to persist data even after a running container is stopped.| 
| LXC	LinuX Containers | is a OS-level virtualization technology that allows creation and running of multiple isolated Linux virtual environments (VE) on a single control host. | 
| Image	| An immutable file that contains the source code, libraries, and dependencies that are necessary for an application to run. Images are templates or blueprints for a container. | 
| Immutability	| Images are read-only; if you change an image, you create a new image. | 
| Microservices	| are a cloud-native architectural approach in which a single application contains many loosely coupled and independently deployable smaller components or services. | 
| Namespace	| A Linux namespace is a Linux kernel feature that isolates and virtualizes system resources. Processes which are restricted to a namespace can only interact with resources or processes that are part of the same namespace. Namespaces are an important part of Docker’s isolation model. Namespaces exist for each type of resource, including networking, storage, processes, hostname control and others. | 
| Operating System Virtualization	| OS-level virtualization is an operating system paradigm in which the kernel allows the existence of multiple isolated user space instances, called containers, zones, virtual private servers, partitions, virtual environments, virtual kernels, or jails. | 
| Private Registry	| restricts access to images so that only authorized users can view and use them. | 
| Registry | is a hosted service containing repositories of images which responds to the Registry API. | 
| Repository	| is a set of Docker images. A repository can be shared by pushing it to a registry server. The different images in the repository can be labelled using tags. | 
| Server Virtualization	| Server virtualization is the process of dividing a physical server into multiple unique and isolated virtual servers by means of a software application. Each virtual server can run its own operating systems independently. |  
| Tag	| A tag is a label applied to a Docker image in a repository. Tags are how various images in a repository are distinguished from each other. | 
