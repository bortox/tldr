---
author: ['David', 'Graham Ashton', 'Seth Falco', 'bl-ue']
date: 1629050349
title: "podman, TLDR Pages"
description: "podman, Simple management tool for pods, containers and images."
categories: "common"
---
> Podman provides a Docker-CLI comparable command-line. Simply put: `alias docker=podman`.

> More information: <https://github.com/containers/podman/blob/main/commands-demo.md>.

- Print out information about containers:

```bash
podman ps
```

- List all containers (both running and stopped):

```bash
podman ps --all
```

- Start one or more containers:

```bash
podman start container_name container_id
```

- Stop one or more running containers:

```bash
podman stop container_name container_id
```

- Pull an image from a registry (defaults to the Docker Hub):

```bash
podman pull image_name:image_tag
```

- Open a shell inside an already running container:

```bash
podman exec --interactive --tty container_name sh
```

- Remove one or more stopped containers:

```bash
podman rm container_name container_id
```

- Display the logs of one or more containers and follow log output:

```bash
podman logs --follow container_name container_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Graham Ashton](mailto:gma@users.noreply.github.com) | podman: update more information link (#6199) The page documenting all the podman subcommands has been moved. This commit updates the [...] | 2021-07-06T13:28:21 | [2588e62937bb](https://github.com/tldr-pages/tldr/commit/2588e62937bbd9992a5585ba8888aabef852aae2)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[David](mailto:animi.vulpis@gmail.com) | podman: add page (#3491) | 2019-11-02T18:46:04 | [e90e6bdf6b08](https://github.com/tldr-pages/tldr/commit/e90e6bdf6b08704f2ecad1d324b3068ea1519914)

