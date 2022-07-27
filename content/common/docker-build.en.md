---
author: ['Seth Falco', 'Ein Verne']
date: 1624652454
title: "docker build, TLDR Pages"
description: "docker build, Build an image from a Dockerfile."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/build/>.

- Build a docker image using the Dockerfile in the current directory:

```bash
docker build .
```

- Build a docker image from a Dockerfile at a specified URL:

```bash
docker build github.com/creack/docker-firefox
```

- Build a docker image and tag it:

```bash
docker build --tag name:tag .
```

- Build a docker image with no build context:

```bash
docker build --tag name:tag - < Dockerfile
```

- Do not use the cache when building the image:

```bash
docker build --no-cache --tag name:tag .
```

- Build a docker image using a specific Dockerfile:

```bash
docker build --file Dockerfile .
```

- Build with custom build-time variables:

```bash
docker build --build-arg HTTP_PROXY=http://10.20.30.2:1234 --build-arg FTP_PROXY=http://40.50.60.5:4567 .
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | docker-build: add example with docker from stdin (#6103) | 2021-06-25T22:20:54 | [c5bc7d08525c](https://github.com/tldr-pages/tldr/commit/c5bc7d08525cef655e84199a20f17facad993b08)
[Ein Verne](mailto:einverne@gmail.com) | docker-build: add page (#3940) | 2020-04-01T02:46:28 | [fecee0d61a50](https://github.com/tldr-pages/tldr/commit/fecee0d61a508a18376a9348c4bd04132ab2834c)

