nsi-docker-rabbitmq
===================

*Node.js Services Integration - Docker image for rabbitmq based on docker-baseimage*

This image contains a bare install of [rabbitmq](https://www.rabbitmq.com).

It is based on [phusion's base image](https://github.com/phusion/baseimage-docker).

Install
-------

    docker pull albanm/nsi-rabbitmq

Usage
-----

    docker run -d -p 5672:5672 -p 15672:15672 -v <data-dir>:/data albanm/nsi-rabbitmq