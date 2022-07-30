---
author: ['Axel Navarro']
date: 1599701362
title: "docker system"
description: "docker system, Manage Docker data and display system-wide information."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/system/>.

- Show help:

```bash
docker system
```

- Show docker disk usage:

```bash
docker system df
```

- Show detailed information on disk usage:

```bash
docker system df --verbose
```

- Remove unused data:

```bash
docker system prune
```

- Remove unused data created more than a specified amount of time in the past:

```bash
docker system prune --filter="until=hourshminutesm"
```

- Display real-time events from the Docker daemon:

```bash
docker system events
```

- Display real-time events from containers streamed as valid JSON Lines:

```bash
docker system events --filter 'type=container' --format 'json .'
```

- Display system-wide information:

```bash
docker system info
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | docker-system: add page (#4310) | 2020-09-10T03:29:22 | [c00548df9396](https://github.com/tldr-pages/tldr/commit/c00548df9396eb6deae125eaeec90c6bd386139c)

