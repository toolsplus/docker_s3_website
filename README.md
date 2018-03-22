# Docker S3_website

[![Docker Build Status](https://img.shields.io/docker/build/toolsplus/docker_s3_website.svg)]()

This repository contains **Dockerfile** to build static websites using [s3_website](https://github.com/laurilehmijoki/s3_website).


## Installation ##

1. Install [Docker](https://www.docker.com)
2. Pull [automated build](https://registry.hub.docker.com/u/toolsplus/scala-sbt-aws) from public [Docker Hub Registry](https://registry.hub.docker.com):
```
docker pull toolsplus/docker_s3_website
```
Alternatively, you can build an image from Dockerfile:
```
docker build -t toolsplus/docker_s3_website github.com/toolsplus/docker_s3_website
```


## Usage ##

```
docker run -it --rm toolsplus/docker_s3_website
```