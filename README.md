# is117-docker
This will get apache server running locally using docker with a public_html folder that you can edit web pages that are then served by apache
You need to clone this repo and be in the directory.

1. [Containerization vs. Virtualization](https://www.ibm.com/cloud/blog/containers-vs-vms)
2. [Signup for Docker](https://www.docker.com)
3. [Install WSL2 and Docker Desktop - Windows Only](https://andrewlock.net/installing-docker-desktop-for-windows/)
4. [Install Docker Desktop - Mac](https://www.docker.com/products/docker-desktop)
5. [Complete the Docker Getting Started - Watch the Videos](https://docs.docker.com/get-started/)
6. Run this Repoitory using Docker to get Apache and a local file share setup
* Instructions:
1. command: docker compose up
2. goto http://locahost:8080

control c (windows stops apache) command c (mac stops apache)

Docker Hub is where you can find images to run with docker.  Try to install ubuntu server 
https://hub.docker.com/search?type=image

docker runing ubuntu server: docker run -it ubuntu:latest
type exit to get out of the ubuntu container

* [Docker and WebStorm](https://www.jetbrains.com/help/idea/docker.html)

* [Docker and Mysql](https://towardsdatascience.com/how-to-run-mysql-using-docker-ed4cebcd90e4)

