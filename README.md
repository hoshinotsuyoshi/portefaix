Portefaix
=========

## Description

Some docker containers.

## Deployment

* Build the container :

        $ docker build -t="<yourname>/<name>" .

* Once the container is available, push it to the [Docker Index](index.docker.io) :

        $ sudo docker login
        $ sudo docker push <yourname>/<name>

# UI

* [DockerUI](https://github.com/crosbymichael/dockerui) could be used to display available containers :

        $ docker pull crosbymichael/dockerui
        $ docker run -d crosbymichael/dockerui -e="http://127.0.0.1:4243"

## Copyright

Copyright (c) Nicolas Lamirault <nicolas.lamirault@gmail.com>
