---
author: ['Ali Malek']
date: 1604241294
title: "docker swarm, TLDR Pages"
description: "docker swarm, A container orchestration tool."
categories: "common"
---
> More information: <https://docs.docker.com/engine/swarm/>.

- Initialize a swarm cluster:

```bash
docker swarm init
```

- Display the token to join a manager or a worker:

```bash
docker swarm join-token worker|manager
```

- Join a new node to the cluster:

```bash
docker swarm join --token token manager_node_url:2377
```

- Remove a worker from the swarm (run inside the worker node):

```bash
docker swarm leave
```

- Display the current CA certificate in PEM format:

```bash
docker swarm ca
```

- Rotate the current CA certificate and display the new certificate:

```bash
docker swarm ca --rotate
```

- Change the valid period for node certificates:

```bash
docker swarm update --cert-expiry hourshminutesmsecondss
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ali Malek](mailto:ali.malek.71@gmail.com) | docker-swarm: add page (#4873) | 2020-11-01T15:34:54 | [3b39f650fee6](https://github.com/tldr-pages/tldr/commit/3b39f650fee6add535d63d24e2ccecb2fea18d44)

