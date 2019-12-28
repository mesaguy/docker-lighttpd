# Alpine based lighttpd service

[![DockerHub Badge](http://dockeri.co/image/mesaguy/lighttpd)](https://hub.docker.com/r/mesaguy/lighttpd)

## Introduction

Simple unprivileged lighttpd implementation.

lighttpd runs on 8080/tcp as the user 'lighttpd', error logs are send to stderr

## Usage

HTTP data can be mounted to /var/www/localhost/htdocs

The /etc/lighttpd/custom.conf (empty by default) is included by /etc/lighttpd/lighttpd.conf and can be overwritten for simple customizations. Otherwise, the /etc/lighttpd/lighttpd.conf file can be overwritten.

Access logs are written to /var/log/lighttpd which should be a mounted volume
