# gunclock on jetty - Dockerfile

Dockerfile for gunclock on jetty.

## build command 
    $ git clone https://github.com/gunman-vagabond/docker_gunclock_jetty.git
    $ cd docker_gunclock_jetty
    $ docker image build -t gunclock_jetty .
    $ docker run -p 30080:8080 gunclock_jetty

## Docker image on Docker Hub

- Docker Hub 

    https://cloud.docker.com/repository/docker/gunman/gunclock_jetty/

- docker run command (example)

    $ docker run -p 30080:8080 gunman/gunclock_jetty

- access (example)

    http://xxxxxxx:30080/gunclock/gunclock

