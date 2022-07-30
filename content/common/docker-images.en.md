---
author: ['Ali Malek', 'Ivan Aracki']
date: 1603908768
title: "docker images"
description: "docker images, Manage Docker images."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/images/>.

- List all Docker images:

```bash
docker images
```

- List all Docker images including intermediates:

```bash
docker images --all
```

- List the output in quiet mode (only numeric IDs):

```bash
docker images --quiet
```

- List all Docker images not used by any container:

```bash
docker images --filter dangling=true
```

- List images that contain a substring in their name:

```bash
docker images "*name*"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ali Malek](mailto:ali.malek.71@gmail.com) | docker-images: add filter example (#4819) | 2020-10-28T19:12:48 | [61cd51518c06](https://github.com/tldr-pages/tldr/commit/61cd51518c06cc909d6d79801078a11d572b953d)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | docker images: add page (#3061) | 2019-06-07T12:14:58 | [697da6604408](https://github.com/tldr-pages/tldr/commit/697da6604408a04245892a79dcb68dac1f0a17aa)

