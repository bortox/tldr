---
author: ['Starbeamrainbowlabs']
date: 1618250129
title: "docker image"
description: "docker image, Manage Docker images."
categories: "common"
---
> See also `docker build`, `docker import`, and `docker pull`.

> More information: <https://docs.docker.com/engine/reference/commandline/image/>.

- List local Docker images:

```bash
docker image ls
```

- Delete unused local Docker images:

```bash
docker image prune
```

- Delete all unused images (not just those without a tag):

```bash
docker image prune --all
```

- Show the history of a local Docker image:

```bash
docker image history image
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | docker-image: add page (#5684) | 2021-04-12T19:55:29 | [c571fa7ce215](https://github.com/tldr-pages/tldr/commit/c571fa7ce215bf44604fb4e689bccb4e2bfc6b55)

