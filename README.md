# docker-tutorial
Docker Tutorial for Beginners https://youtu.be/pTFZFxd4hOI

## What is docker
A platform for building, running and shipping applications in a consisten manner.
With docker we can easily package up our application with everything it needs and run it anywhere on any machine with docker.
In a nutshell, docker helps us consistently build run and ship our applications.

## Virtual machines vs containers
A container is an isolated environment for running an application
A virtual machine is an abstraction of a machine (physical hardware)

## Docker architecture
Docker uses a client server architecture so it has a client component that talks to a server component using a restful api. The server also called the docker engine sits on the background and takes care of building and running docker containers. Technically a container is just a process like other processes running on your computer. All these containers share the kernel of the host.
