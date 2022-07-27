---
author: ['Axel Navarro']
date: 1600407321
title: "docker rmi, TLDR Pages"
description: "docker rmi, Remove one or more Docker images."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/rmi/>.

- Show help:

```bash
docker rmi
```

- Remove one or more images given their names:

```bash
docker rmi image1 image2 ...
```

- Force remove an image:

```bash
docker rmi --force image
```

- Remove an image without deleting untagged parents:

```bash
docker rmi --no-prune image
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | docker-rmi: add page (#4339) | 2020-09-18T07:35:21 | [dca3bd2d0491](https://github.com/tldr-pages/tldr/commit/dca3bd2d04915cd8e880f694210f47330c083888)

