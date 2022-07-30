---
author: ['Gaurav Chaudhari']
date: 1603910094
title: "docker service"
description: "docker service, Manage the services on a docker daemon."
categories: "common"
---
> More information: <https://docs.docker.com/engine/reference/commandline/service/>.

- List the services on a docker daemon:

```bash
docker service ls
```

- Create a new service:

```bash
docker service create --name service_name image:tag
```

- Display detailed information of a space-separated list of services:

```bash
docker service inspect service_name|ID
```

- List the tasks of a space-separated list of services:

```bash
docker service ps service_name|ID
```

- Scale to a specific number of replicas for a space-separated list of services:

```bash
docker service scale service_name=count_of_replicas
```

- Remove a space-separated list of services:

```bash
docker service rm service_name|ID
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gaurav Chaudhari](mailto:capristar02@gmail.com) | docker-service: add page (#4800) | 2020-10-28T19:34:54 | [df22df93b224](https://github.com/tldr-pages/tldr/commit/df22df93b2241d30232351ec23d26f505a0431b5)

