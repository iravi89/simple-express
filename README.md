# Simple Node
## Overview
This is a very simple, bare-bones NodeJS project created for you to use with Docker. In this excercise we we are creating reverse proxy.
A reverse proxy proxy is used to route traffic from one endpoint to multiple endpoints

## Reverse Proxy

   * A single interface that forwards requests on behalf of the client and appears to the client as the origin of the responses.
   * Useful for abstracting multiple microservices to appear as a single resource.


## Local Setup
* Install dependencies: `npm install`
* Run server: `node server.js`

## Container Setup
* Build image: `docker build .`
* Run container with image: `docker run {image_id}` where `image_id` can be retrieved by running `docker images` and found under the column `IMAGE ID`

## Container teardown
* Remove container: `docker kill {container_id}` where `container_id` can be retrieved by running `docker ps` and found under the column `CONTAINER ID`
