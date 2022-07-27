---
author: ['Axel Navarro']
date: 1645346226
title: "docker volume, TLDR Pages"
description: "docker volume, Manage Docker volumes."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/volume/>.

- Create a volume:

```bash
docker volume create volume_name
```

- Create a volume with a specific label:

```bash
docker volume create --label label volume_name
```

- Create a `tmpfs` volume a size of 100 MiB and an uid of 1000:

```bash
docker volume create --opt type=tmpfs --opt device=tmpfs --opt o=size=100m,uid=1000 volume_name
```

- List all volumes:

```bash
docker volume ls
```

- Remove a volume:

```bash
docker volume rm volume_name
```

- Display information about a volume:

```bash
docker volume inspect volume_name
```

- Remove all unused local volumes:

```bash
docker volume prune
```

- Display help for a subcommand:

```bash
docker volume subcommand --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | docker-volume: add page (#7771) | 2022-02-20T09:37:06 | [ae90383189b9](https://github.com/tldr-pages/tldr/commit/ae90383189b925ebe3fb79f6dfea62d542941bf2)

