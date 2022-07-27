---
author: ['258204', 'Joachim Schwarm']
date: 1634445390
title: "docker login, TLDR Pages"
description: "docker login, Log into a docker registry."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/login/>.

- Interactively log into a registry:

```bash
docker login
```

- Log into a registry with a specific username (user will be prompted for a password):

```bash
docker login --username username
```

- Log into a registry with username and password:

```bash
docker login --username username --password password server
```

- Log into a registry with password from stdin:

```bash
echo "password" | docker login --username username --password-stdin
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Joachim Schwarm](mailto:joachim@schwarm.co) | docker-*: add German translation (#6833) | 2021-10-17T06:36:30 | [32580f24e63d](https://github.com/tldr-pages/tldr/commit/32580f24e63daa8abf77cffe6bc7dac55911fb3a)
[258204](mailto:71364336+258204@users.noreply.github.com) | docker-login: add page (#6137) | 2021-06-23T10:05:47 | [6f1cd48ae2f4](https://github.com/tldr-pages/tldr/commit/6f1cd48ae2f4ed6791fbe8e280fdce7ea0902276)

