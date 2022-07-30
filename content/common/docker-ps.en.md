---
author: ['Axel Navarro']
date: 1599581992
title: "docker ps"
description: "docker ps, List Docker containers."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/ps/>.

- List currently running docker containers:

```bash
docker ps
```

- List all docker containers (running and stopped):

```bash
docker ps --all
```

- Show the latest created container (includes all states):

```bash
docker ps --latest
```

- Filter containers that contain a substring in their name:

```bash
docker ps --filter="name=name"
```

- Filter containers that share a given image as an ancestor:

```bash
docker ps --filter "ancestor=image:tag"
```

- Filter containers by exit status code:

```bash
docker ps --all --filter="exited=code"
```

- Filter containers by status (created, running, removing, paused, exited and dead):

```bash
docker ps --filter="status=status"
```

- Filter containers that mount a specific volume or have a volume mounted in a specific path:

```bash
docker ps --filter="volume=path/to/directory" --format "table .ID\t.Image\t.Names\t.Mounts"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | docker-ps: add page (#4306) | 2020-09-08T18:19:52 | [b6b5997b6c4f](https://github.com/tldr-pages/tldr/commit/b6b5997b6c4fd9e830a8474a0bbab651ed415e72)

