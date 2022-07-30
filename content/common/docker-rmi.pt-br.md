---
author: ['caduvieira']
date: 1633698984
title: "docker rmi"
description: "docker rmi, Remove uma ou mais imagens Docker."
categories: "common"
---
> Mais informações: <https://docs.docker.com/engine/reference/commandline/rmi/>.

- Exibe a ajuda:

```bash
docker rmi
```

- Remove uma ou mais imagens pelo seus nomes:

```bash
docker rmi imagem1 imagem2 ...
```

- Remove forçadamente uma imagem:

```bash
docker rmi --force imagem
```

- Remove uma imagem sem apagar suas imagens pais que não possuem tags:

```bash
docker rmi --no-prune imagem
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[caduvieira](mailto:3831408+caduvieira@users.noreply.github.com) | docker-cp, docker-rmi, docker-stats: add pt_BR translation (#6783) | 2021-10-08T15:16:24 | [37b005c3623e](https://github.com/tldr-pages/tldr/commit/37b005c3623ec0332bbc69dd41a251087f98d55c)

