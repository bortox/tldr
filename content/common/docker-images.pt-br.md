---
author: ['Carlos Vieira']
date: 1604605098
title: "docker images, TLDR Pages"
description: "docker images, Gerencia imagens Docker."
categories: "common"
---
> Mais informações: <https://docs.docker.com/engine/reference/commandline/images/>.

- Lista todas as imagens Docker:

```bash
docker images
```

- Lista todas as imagens Docker incluíndo imagens intermedirárias:

```bash
docker images --all
```

- Lista no modo silencioso (somente IDs numéricos):

```bash
docker images --quiet
```

- Lista todas as imagens Docker não usadas por nenhum container:

```bash
docker images --filter dangling=true
```

- Lista imagens que contenham um substring no seu nome:

```bash
docker images "*nome*"
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Carlos Vieira](mailto:3831408+caduvieira@users.noreply.github.com) | docker-images: add pt_BR translation | 2020-11-05T20:38:18 | [1a989dc0751c](https://github.com/tldr-pages/tldr/commit/1a989dc0751cbf0c4ef63b690870084ac253e6f1)

