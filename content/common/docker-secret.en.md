---
author: ['Ali Malek']
date: 1605037191
title: "docker secret"
description: "docker secret, Manage Docker swarm secrets."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/secret/>.

- Create a new secret from stdin:

```bash
command | docker secret create secret_name -
```

- Create a new secret from a file:

```bash
docker secret create secret_name path/to/file
```

- List all secrets:

```bash
docker secret ls
```

- Display detailed information on one or multiple secrets in a human friendly format:

```bash
docker secret inspect --pretty secret_name1 secret_name2 ...
```

- Remove one or more secrets:

```bash
docker secret rm secret_name1 secret_name2 ...
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ali Malek](mailto:ali.malek.71@gmail.com) | docker-secret: add page (#4933) | 2020-11-10T20:39:51 | [4f20fdcd6495](https://github.com/tldr-pages/tldr/commit/4f20fdcd64955e2a9ed6f0aa0d6534c7c41ece6f)

