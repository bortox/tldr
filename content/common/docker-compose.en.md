---
author: ['Locour', 'Schneider', 'Pavel Tarnopolsky', 'Ali Malek', 'Arif Waram', 'Marco Bonelli']
date: 1634145825
title: "docker-compose"
description: "docker-compose, Run and manage multi container docker applications."
categories: "common"
---
> More information: <https://docs.docker.com/compose/reference/>.

- List all running containers:

```bash
docker-compose ps
```

- Create and start all containers in the background using a `docker-compose.yml` file from the current directory:

```bash
docker-compose up -d
```

- Start all containers, rebuild if necessary:

```bash
docker-compose up --build
```

- Start all containers using an alternate compose file:

```bash
docker-compose --file path/to/file up
```

- Stop all running containers:

```bash
docker-compose stop
```

- Stop and remove all containers, networks, images, and volumes:

```bash
docker-compose down --rmi all --volumes
```

- Follow logs for all containers:

```bash
docker-compose logs --follow
```

- Follow logs for a specific container:

```bash
docker-compose logs --follow container_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Locour](mailto:Locour@users.noreply.github.com) | docker-compose: add German translation (#6978) | 2021-10-13T19:23:45 | [9e781d59bed6](https://github.com/tldr-pages/tldr/commit/9e781d59bed60863bbf0de866c5f181d8622514e)
[Ali Malek](mailto:ali.malek.71@gmail.com) | docker-compose: add new example (#4817) | 2020-10-24T14:59:15 | [ff06977da29b](https://github.com/tldr-pages/tldr/commit/ff06977da29b0a48c3cd3112fede85adfd577549)
[Arif Waram](mailto:ninearif@hotmail.com) | docker-compose: add --rmi all --volumes (#3498) add "--rmi all --volumes" parameters to docker-compose down command, in order to match [...] | 2019-11-05T02:16:46 | [8a8646884c59](https://github.com/tldr-pages/tldr/commit/8a8646884c59c8032651abccc8299823f7e088b3)
[Arif Waram](mailto:ninearif@hotmail.com) | docker-compose: add docker-compose ps(#3507) | 2019-10-30T13:59:17 | [e58f188c3e60](https://github.com/tldr-pages/tldr/commit/e58f188c3e607e21174e1d573c157718866a171c)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | docker pages: add homepages | 2019-04-15T01:35:17 | [b89d4f06e39a](https://github.com/tldr-pages/tldr/commit/b89d4f06e39a8d6bbabf0f87f33b9888950df655)
[Pavel Tarnopolsky](mailto:paveltarno@gmail.com) | docker-compose: add page (#1460) | 2017-08-31T10:55:23 | [ed81078a21ef](https://github.com/tldr-pages/tldr/commit/ed81078a21ef187e223f3047881e4a24c8ef20f4)

