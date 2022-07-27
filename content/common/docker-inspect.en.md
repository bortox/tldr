---
author: ['Axel Navarro']
date: 1600794840
title: "docker inspect, TLDR Pages"
description: "docker inspect, Return low-level information on Docker objects."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/inspect/>.

- Show help:

```bash
docker inspect
```

- Display information about a container, image, or volume using a name or ID:

```bash
docker inspect container|image|ID
```

- Display a container's IP address:

```bash
docker inspect --format='range .NetworkSettings.Networks.IPAddressend' container
```

- Display the path to the container's log file:

```bash
docker inspect --format='.LogPath' container
```

- Display the image name of the container:

```bash
docker inspect --format='.Config.Image' container
```

- Display the configuration information as JSON:

```bash
docker inspect --format='json .Config' container
```

- Display all port bindings:

```bash
docker inspect --format='range $p, $conf := .NetworkSettings.Ports $p -> (index $conf 0).HostPort end' container
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | docker-inspect: add page (#4337) | 2020-09-22T19:14:00 | [53ec1f431811](https://github.com/tldr-pages/tldr/commit/53ec1f43181171e9bb855ab4229aaa15f870e38d)

