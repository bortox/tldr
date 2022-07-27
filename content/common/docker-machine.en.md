---
author: ['Marco Bonelli', 'Schneider', 'Ivan Aracki']
date: 1559564381
title: "docker-machine, TLDR Pages"
description: "docker-machine, Create and manage machines running Docker."
categories: "common"
---
> More information: <https://docs.docker.com/machine/reference/>.

- List currently running docker machines:

```bash
docker-machine ls
```

- Create a new docker machine with specific name:

```bash
docker-machine create name
```

- Get the status of a machine:

```bash
docker-machine status name
```

- Start a machine:

```bash
docker-machine start name
```

- Stop a machine:

```bash
docker-machine stop name
```

- Inspect information about a machine:

```bash
docker-machine inspect name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | docker pages: add homepages | 2019-04-15T01:35:17 | [b89d4f06e39a](https://github.com/tldr-pages/tldr/commit/b89d4f06e39a8d6bbabf0f87f33b9888950df655)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | docker-machine: add page (#2582) | 2018-11-13T18:44:31 | [298ece112d64](https://github.com/tldr-pages/tldr/commit/298ece112d6413bf4e7101a62fff359ee1bf3286)

