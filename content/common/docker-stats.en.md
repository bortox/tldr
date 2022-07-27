---
author: ['Ali Malek', 'Seth Falco']
date: 1629050349
title: "docker stats, TLDR Pages"
description: "docker stats, Display a live stream of resource usage statistics for containers."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/stats/>.

- Display a live stream for the statistics of all running containers:

```bash
docker stats
```

- Display a live stream of statistics for a space-separated list of containers:

```bash
docker stats container_name
```

- Change the columns format to display container's CPU usage percentage:

```bash
docker stats --format ".Name:\t.CPUPerc"
```

- Display statistics for all containers (both running and stopped):

```bash
docker stats --all
```

- Disable streaming stats and only pull the current stats:

```bash
docker stats --no-stream
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Ali Malek](mailto:ali.malek.71@gmail.com) | docker-stats: add page (#4939) | 2020-11-27T01:56:28 | [e6c0dfb59188](https://github.com/tldr-pages/tldr/commit/e6c0dfb591883573fd793e931e0cb77ee61d1322)

