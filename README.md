# Dockerized go server

This repository contains a Dockerfile for containerizing ThoughtWorks' [Go](http://go.cd) continuous delivery server.

# Usage

To run one or more agents, repeat the following command to launch as many as you need:

    docker run -d --name go-server -p 8153:80 patforna/go-server

# Building from scratch

To build the image from scratch, execute the command below (replace 14.1.0 with new version):

    docker build -t patforna/go-server:14.1.0 .