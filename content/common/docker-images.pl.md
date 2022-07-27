---
author: ['Michal']
date: 1587299476
title: "docker images, TLDR Pages"
description: "docker images, Zarządzaj obrazami Dockera."
categories: "common"
---
> Więcej informacji: <https://docs.docker.com/engine/reference/commandline/images/>.

- Wyświetl wszystkie obrazy Docker:

```bash
docker images
```

- Wyświetl wszystkie obrazy Dockera, w tym intermediates:

```bash
docker images -a
```

- Wyświetl dane wyjściowe w trybie quiet (tylko identyfikatory numeryczne):

```bash
docker images -q
```

- Wyświetl wszystkie obrazy Docker nieużywane przez żaden kontener:

```bash
docker images --filter dangling=true
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Michal](mailto:mich.biesiada@gmail.com) | update docker-images updated | 2020-04-19T14:31:16 | [4f8a26b2ae5b](https://github.com/tldr-pages/tldr/commit/4f8a26b2ae5bebdb7341b8c2cb7644bfbb0ad1dc)
[Michal](mailto:mich.biesiada@gmail.com) | create docker-images.md initial | 2020-04-19T14:31:16 | [785913b3929b](https://github.com/tldr-pages/tldr/commit/785913b3929b30783d41dc8c7f16bab87d728f31)

