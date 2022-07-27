---
author: ['Henryk Nowakowski']
date: 1576406848
title: "docker logs, TLDR Pages"
description: "docker logs, Print container logs."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/logs>.

- Print logs from a container:

```bash
docker logs container_name
```

- Print logs and follow them:

```bash
docker logs -f container_name
```

- Print last 5 lines:

```bash
docker logs container_name --tail 5
```

- Print logs and append them with timestamps:

```bash
docker logs -t container_name
```

- Print logs from a certain point in time of container execution (i.e. 23m, 10s, 2013-01-02T13:23:37):

```bash
docker logs container_name --until time
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Henryk Nowakowski](mailto:hjnowakowski@gmail.com) | docker-logs: add page (#3656) | 2019-12-15T11:47:28 | [5de24a77a178](https://github.com/tldr-pages/tldr/commit/5de24a77a178e559fe1d6dafe76e420f7816e176)

