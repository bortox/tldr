---
author: ['Axel Navarro']
date: 1634140631
title: "docker commit, TLDR Pages"
description: "docker commit, Create a new image from a container’s changes."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/commit/>.

- Create an image from a specific container:

```bash
docker commit container image:tag
```

- Apply a `CMD` Dockerfile instruction to the created image:

```bash
docker commit --change="CMD command" container image:tag
```

- Apply an `ENV` Dockerfile instruction to the created image:

```bash
docker commit --change="ENV name=value" container image:tag
```

- Create an image with a specific author in the metadata:

```bash
docker commit --author="author" container image:tag
```

- Create an image with a specific comment in the metadata:

```bash
docker commit --message="comment" container image:tag
```

- Create an image without pausing the container during commit:

```bash
docker commit --pause=false container image:tag
```

- Display help:

```bash
docker commit --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | docker-commit: add page (#6976) | 2021-10-13T17:57:11 | [4bee9674ea31](https://github.com/tldr-pages/tldr/commit/4bee9674ea311e740634c758096060f627384fc9)

