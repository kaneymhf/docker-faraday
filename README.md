# Docker Image for Faraday IDE Server (Community Edition)

## Description

Faraday IDE is a collaborative pentesting platform provided by Infobyte LLC.
This Dockerfile will build a container which will run the free community 
edition of the server.

## Setup

```
docker build . -t faraday-server
docker run -p 5985:5985  --name faraday-server faraday-server
```
