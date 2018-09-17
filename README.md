[![CircleCI](https://circleci.com/gh/bitnami/bitnami-docker-nginx-ingress-controller/tree/master.svg?style=shield)](https://circleci.com/gh/bitnami/bitnami-docker-nginx-ingress-controller/tree/master)

# What is NGINX Ingress Controller?

NGINX Ingress Controller is an Ingress controller that uses NGINX to manage external access to HTTP services in a Kubernetes cluster.

https://github.com/kubernetes/ingress-nginx

# TL;DR;

Deploy NGINX Ingress Controller for Kubernetes on your [Kubernetes cluster](https://kubernetes.io/docs/concepts/services-networking/ingress/).

```bash
$ docker run --name nginx-ingress-controller bitnami/nginx-ingress-controller:latest
```

# Why use Bitnami Images?

* Bitnami closely tracks upstream source changes and promptly publishes new versions of this image using our automated systems.
* With Bitnami images the latest bug fixes and features are available as soon as possible.
* Bitnami containers, virtual machines and cloud images use the same components and configuration approach - making it easy to switch between formats based on your project needs.
* Bitnami images are built on CircleCI and automatically pushed to the Docker Hub.
* All our images are based on [minideb](https://github.com/bitnami/minideb) a minimalist Debian based container image which gives you a small base container image and the familiarity of a leading linux distribution.

# Supported tags and respective `Dockerfile` links

> NOTE: Debian 8 images have been deprecated in favor of Debian 9 images. Bitnami will not longer publish new Docker images based on Debian 8.


* [`0-ol-7`, `0.19.0-ol-7-r7` (0/ol-7/Dockerfile)](https://github.com/bitnami/bitnami-docker-nginx-ingress-controller/blob/0.19.0-ol-7-r7/0/ol-7/Dockerfile)
* [`0-debian-9`, `0.19.0-debian-9-r6`, `0`, `0.19.0`, `0.19.0-r6`, `latest` (0/debian-9/Dockerfile)](https://github.com/bitnami/bitnami-docker-nginx-ingress-controller/blob/0.19.0-debian-9-r6/0/debian-9/Dockerfile)

Subscribe to project updates by watching the [bitnami/nginx-ingress-controller GitHub repo](https://github.com/bitnami/bitnami-docker-nginx-ingress-controller).

# Configuration

For further documentation, please check [here](https://github.com/kubernetes/ingress-nginx).

# Contributing

We'd love for you to contribute to this container. You can request new features by creating an [issue](https://github.com/bitnami/bitnami-docker-nginx-ingress-controller/issues), or submit a [pull
request](https://github.com/bitnami/bitnami-docker-nginx-ingress-controller/pulls) with your contribution.

# Issues

If you encountered a problem running this container, you can file an [issue](https://github.com/bitnami/bitnami-docker-nginx-ingress-controller/issues). For us to provide better support, be sure to include the following information in your issue:

- Host OS and version
- Docker version (`docker version`)
- Output of `docker info`
- Version of this container
- The command you used to run the container, and any relevant output you saw (masking any sensitive information)

# License
Copyright 2018 Bitnami

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
