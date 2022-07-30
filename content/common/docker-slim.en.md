---
author: ['Axel Navarro']
date: 1632549230
title: "docker-slim"
description: "docker-slim, Analyze and optimize Docker images."
categories: "common"
---
> More information: <https://github.com/docker-slim/docker-slim>.

- Start DockerSlim on interactive mode:

```bash
docker-slim
```

- Analyze Docker layers from a specific image:

```bash
docker-slim xray --target image:tag
```

- Lint a Dockerfile:

```bash
docker-slim lint --target path/to/Dockerfile
```

- Analyze and generate an optimized Docker image:

```bash
docker-slim build image:tag
```

- Display help for a subcommand:

```bash
docker-slim subcommand --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | docker-slim: add page (#6590) | 2021-09-25T07:53:50 | [c020dab2c2cf](https://github.com/tldr-pages/tldr/commit/c020dab2c2cf6c0fc5f2019ee15fb6595cf3b31f)

