---
author: ['Gaurav Chaudhari', 'Seth Falco']
date: 1629050349
title: "docker network, TLDR Pages"
description: "docker network, Create and manage docker networks."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/network/>.

- List all available and configured networks on docker daemon:

```bash
docker network ls
```

- Create a user-defined network:

```bash
docker network create --driver driver_name network_name
```

- Display detailed information of a space-separated list of networks:

```bash
docker network inspect network_name
```

- Connect a container to a network using a name or ID:

```bash
docker network connect network_name container_name|ID
```

- Disconnect a container from a network:

```bash
docker network disconnect network_name container_name|ID
```

- Remove all unused (not referenced by any container) networks:

```bash
docker network prune
```

- Remove a space-separated list of unused networks:

```bash
docker network rm network_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Gaurav Chaudhari](mailto:capristar02@gmail.com) | docker-network: add page (#4633) | 2020-10-13T12:58:53 | [a00334e5ad48](https://github.com/tldr-pages/tldr/commit/a00334e5ad489d26bfdf07e7cd5f7e80c5390065)

