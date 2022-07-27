---
author: ['Matthew Peveler']
date: 1609624083
title: "docker container, TLDR Pages"
description: "docker container, Manage Docker containers."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/container/>.

- List currently running Docker containers:

```bash
docker container ls
```

- Start one or more stopped containers:

```bash
docker container start container1_name container2_name
```

- Kill one or more running containers:

```bash
docker container kill container_name
```

- Stop one or more running containers:

```bash
docker container stop container_name
```

- Pause all processes within one or more containers:

```bash
docker container pause container_name
```

- Display detailed information on one or more containers:

```bash
docker container inspect container_name
```

- Export a container's filesystem as a tar archive:

```bash
docker container export container_name
```

- Create a new image from a container's changes:

```bash
docker container commit container_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Matthew Peveler](mailto:matt.peveler@gmail.com) | docker-container: fix filename spelling (#5067) | 2021-01-02T22:48:03 | [652d4b63a1ee](https://github.com/tldr-pages/tldr/commit/652d4b63a1ee830b47f359130f9c9e2e8f7facb0)

