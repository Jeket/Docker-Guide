# Chapter 1: Docker Introduction and Getting Started:
This tutorial walks you through the introduction to docker and how to get started with it. 

# Definition: 
Docker is a set of the platform as a service tools. It utilizes the concept of OS-level virtualization. The software is delivered in the form of packages called Containers. The OS-level virtualization is called containerization. One interesting thing about containers is that each container is isolated from each other. To reach the isolation each container is bundled with its own configuration and requirements. 
A container is the standard unit for software with all the code and required dependencies. This enables quick and reliable computation.

# What’s so special about Docker:

<center>You can just use the production environment to locally run the products.
                           & 
              Docker is Open Source!</center>
<b><a href="https://www.docker.com/community/open-source"> More Here</a></b>


<i>Fig. 1 gives a quick look at an abstract architecture that describes containers. </i>

Docker is analogous to an operating system for containers. Containers wrap up all dependencies to run a software. Irrespective of the presence of the dependencies on the local machine, dockers allow running the instance of containers which allow running the application needing those dependencies. 

EXAMPLE: Suppose on the Linux terminal we run a tree command which is not yet installed, it throws a not found error. But we can run the instance of a container which will allow running the tree command. 


![drawing](https://github.com/josharsh/Docker-Guide/blob/master/Resources/architecture.PNG)
<i><Center>Fig 1: Abstract Architecture of Docker</center></i>


Before we dive into Docker and how to use it. Let’s dive in to learn more about why Docker was introduced and what problems did it actually solve to gain tremendous popularity.

## A Sneak Peek into Adaption of Docker: 
The technology hasn’t always been the same as we see it today. A decade ago there was one way of production and development. It was very much standardized for all the applications. Applications were majorly built using Java or .NET frameworks. The applications were deployed to a single server. This was largely using Monolithic architecture. The monolithic architecture is something that builds from a single piece of material. Docker was introduced to shift towards Microservices.
