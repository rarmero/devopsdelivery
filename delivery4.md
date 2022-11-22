## Client App php dockerized


# docker file

FROM php:8.0-apache as base

COPY ./src /var/www/html


![doker image](/images/docker1.png "docker image caption")


[source code](https://github.com/rarmero/frontendphp/tree/main) in GitHub.

## Run App

options:

1. consume a rest api hosted in elastic

![client](/images/docker2.png "client caption")


2. consume a rest api in docker


![client](/images/docker3.png "containers caption")

![client](/images/docker4.png "web page captions")


