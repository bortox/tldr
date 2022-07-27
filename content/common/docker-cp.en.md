---
author: ['taryn']
date: 1616161701
title: "docker cp, TLDR Pages"
description: "docker cp, Copy files or directories between host and container filesystems."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/cp>.

- Copy a file or directory from the host to a container:

```bash
docker cp path/to/file_or_directory_on_host container_name:path/to/file_or_directory_in_container
```

- Copy a file or directory from a container to the host:

```bash
docker cp container_name:path/to/file_or_directory_in_container path/to/file_or_directory_on_host
```

- Copy a file or directory from the host to a container, following symlinks (copies the symlinked files directly, not the symlinks themselves):

```bash
docker cp --follow-link path/to/symlink_on_host container_name:path/to/file_or_directory_in_container
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[taryn](mailto:4861023+phrohdoh@users.noreply.github.com) | docker-cp: add page (#5468) | 2021-03-19T14:48:21 | [2cf45c19cfd8](https://github.com/tldr-pages/tldr/commit/2cf45c19cfd829b55ef3bd6ca70ffd46b163f299)

