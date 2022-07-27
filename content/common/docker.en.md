---
author: ['Waldir Pimenta', 'Rajiv Nair', 'Schneider', 'Jeef', 'Alex Flores', 'Marco Bonelli', 'Ruben Vereecken', 'Shih Yu Ho', 'David (Doojin) Jung', 'Larry Lu', 'Raizo62', 'Matthew Peveler', 'Seth Falco', 'marchersimon', 'Luke Yeager']
date: 1640867821
title: "docker, TLDR Pages"
description: "docker, Manage Docker containers and images."
categories: "common"
---
> Some subcommands such as `docker run` have their own usage documentation.

> More information: <https://docs.docker.com/engine/reference/commandline/cli/>.

- List all docker containers (running and stopped):

```bash
docker ps --all
```

- Start a container from an image, with a custom name:

```bash
docker run --name container_name image
```

- Start or stop an existing container:

```bash
docker start|stop container_name
```

- Pull an image from a docker registry:

```bash
docker pull image
```

- Display the list of already downloaded images:

```bash
docker images
```

- Open a shell inside a running container:

```bash
docker exec -it container_name sh
```

- Remove a stopped container:

```bash
docker rm container_name
```

- Fetch and follow the logs of a container:

```bash
docker logs -f container_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Raizo62](mailto:silicium62-github@yahoo.fr) | docker: add docker images example (#7567) | 2021-12-30T13:37:01 | [f126048f0358](https://github.com/tldr-pages/tldr/commit/f126048f03580200edf9ad8fd66d7d134b3779d9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | docker pages: add homepages | 2019-04-15T01:35:17 | [b89d4f06e39a](https://github.com/tldr-pages/tldr/commit/b89d4f06e39a8d6bbabf0f87f33b9888950df655)
[Matthew Peveler](mailto:matt.peveler@gmail.com) | docker: simplify examples (#2597) | 2018-12-13T10:47:48 | [1fe90c65d6f5](https://github.com/tldr-pages/tldr/commit/1fe90c65d6f55f9977719fb734bdc8176e047922)
[Larry Lu](mailto:pudding850806@gmail.com) | docker: pull image (#2586) | 2018-11-13T19:12:03 | [f8c184402b26](https://github.com/tldr-pages/tldr/commit/f8c184402b263b5a6da4dac5ec9a6cc350640e30)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | docker: combine start/stop, add basic run example (#2363) The start and stop examples are pretty much identical, so it doesn't make [...] | 2018-10-01T18:20:57 | [a6fe2179efa0](https://github.com/tldr-pages/tldr/commit/a6fe2179efa00b1e0fed15b2c720bd992713feb1)
[Shih Yu Ho](mailto:methodho@gmail.com) | docker: add docker container logs example (#1680) | 2017-11-27T19:14:42 | [191666c79479](https://github.com/tldr-pages/tldr/commit/191666c79479ae7e387e776164a2aea7d1f9ad10)
[David (Doojin) Jung](mailto:d.jung460@gmail.com) | docker: update docker commands to conform to Docker 1.13 (#1505) | 2017-09-28T11:25:00 | [a6f0dfbf3184](https://github.com/tldr-pages/tldr/commit/a6f0dfbf3184dc7d8dd2f35cb51214f1e8f29bd4)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | docker: minor tweak to first description change "List" from a noun to a verb, to match the project's guidelines. | 2017-04-28T00:55:32 | [45d9ef5b6a64](https://github.com/tldr-pages/tldr/commit/45d9ef5b6a649054aa3fedebd34b509500428075)
[Jeef](mailto:jeeftor@users.noreply.github.com) | docker: added rm command (#1297) | 2017-03-16T05:37:17 | [7103d8fa3170](https://github.com/tldr-pages/tldr/commit/7103d8fa3170b0dc371ab8cf0e295e9f8cbc6c48)
[Luke Yeager](mailto:lukeyeager@users.noreply.github.com) | Update docker description | 2016-01-20T18:09:54 | [7bfebeae66d1](https://github.com/tldr-pages/tldr/commit/7bfebeae66d101b4ebb20cdbfc8e0ecd833e3192)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Alex Flores](mailto:eflores@mdsol.com) | adds commands for working with images | 2015-12-29T17:14:13 | [3d7f9aebfa31](https://github.com/tldr-pages/tldr/commit/3d7f9aebfa313cb7e91077dd17d53eb60726ee68)
[Rajiv Nair](mailto:rnair@rnair.local) | Add Docker Added commonly used docker commands to list/start/stop containers. | 2015-12-27T19:12:21 | [c69b74e04846](https://github.com/tldr-pages/tldr/commit/c69b74e04846804d44d2a9b12bf7cdb52aedd31a)

