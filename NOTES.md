## What is Docker
Docker is a platform for building running and shipping applications in a consistent manner. If you application is running on your machine it will readily work on another machine

### Why your application will run on you machine and not on deployment
- One or more files is not included in your deployment
- If your target machine is running a different version of software that your applications needs
- Development environmental variables

## Virtual Machines vs Containers
A container is an isolated environment for running an application - (they are more light weight than OS)
A virtual machine is an abstraction of a machine (physical machine)

## Docker Architecture
uses a client server architecture (CLIENT ---REST API---> DOCKER ENGINE)

## Image
what consists a docker image:
- A cut-down OS
- A runtime environment (eg Node)
- Application files
- Third party libraries
- Environmental variables
