# dockerized-docs-sensu

# What is it?
Dockerzied Sensu documentation for offline use.

# Image description
- Base image: `python:2.7.13-alpine`.
- The most current sensu-mkdocs `master` branch is cloned and built using MkDocs.

# How to use this image

```console
$ docker run -d genadipost/dockerized-docs-sensu

```

You can test it by visiting http://container-ip:80
