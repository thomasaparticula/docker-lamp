# LEMP stack with Docker Toolbox

## Overview
This is my development environment which run a Linux [LEMP stack](https://lemp.io/) that work on most of my PHP projects. All the Docker images are based on Alpine Linux to get something that remains light for disk space.

- Container web: Nginx latest (~55Mb)
- Container php: PHP7 with FPM and all common PHP extensions (~65Mb)
- Container db: MariaDB (~175Mb)
- Container mail: Maildev (~35Mb)
- Container cache: Memcached/Redis (~15Mb)

## Installation

* [on OSX](doc/install-osx.md)
* [on Linux](doc/install-linux.md)

## What next?

* [Post configuration](doc/config.md)
* [Aliases and CLI](doc/aliases.md)

## Read further
* http://mmenozzi.github.io/2016/01/22/php-web-development-with-docker/
* https://github.com/nerdpress-org/docker-sf3
* http://stackoverflow.com/questions/40012198/docker-custom-dns-resolve-among-containers