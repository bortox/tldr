---
author: ['Lucas Gabriel Schneider', 'Axel Navarro']
date: 1612112718
title: "docker start, TLDR Pages"
description: "docker start, Start one or more stopped containers."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/start/>.

- Show help:

```bash
docker start
```

- Start a docker container:

```bash
docker start container
```

- Start a container, attaching stdout and stderr and forwarding signals:

```bash
docker start --attach container
```

- Start one or more space-separated containers:

```bash
docker start container(s)
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Axel Navarro](mailto:navarroaxel@gmail.com) | docker-start: add page (#4338) | 2020-09-15T12:37:28 | [dcb5d4c54740](https://github.com/tldr-pages/tldr/commit/dcb5d4c54740d99dd9f4aa6c7fc69625da3599ec)

