---
author: ['Carlos Vieira']
date: 1604605098
title: "docker ps, TLDR Pages"
description: "docker ps, Lista os containers Docker."
categories: "common"
---
> Mais informações: <https://docs.docker.com/engine/reference/commandline/ps/>.

- Lista containers docker em execução:

```bash
docker ps
```

- Lista todos containers docker (em execução e parados):

```bash
docker ps --all
```

- Lista os últimos containers criados (incluí todos os estados):

```bash
docker ps --latest
```

- Filtra os containers que contém uma substring no seu nome:

```bash
docker ps --filter="name=nome"
```

- Filtra todos os containers que possuem uma imagem antepassada:

```bash
docker ps --filter "ancestor=imagem:tag"
```

- Filtra containers que tenha o código de saída:

```bash
docker ps --all --filter="exited=código"
```

- Filtra containers por estado (criado, execução, removendo, pausado, finalizado e morto):

```bash
docker ps --filter="status=estado"
```

- Filtra containers que contenham um volume específico ou montado em um caminho específico:

```bash
docker ps --filter="volume=caminho/para/diretório" --format "table .ID\t.Image\t.Names\t.Mounts"
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Carlos Vieira](mailto:3831408+caduvieira@users.noreply.github.com) | docker-ps: add pt_BR translation | 2020-11-05T20:38:18 | [405e45033d25](https://github.com/tldr-pages/tldr/commit/405e45033d25a91001a2ee7fa2ad9c11a8c52059)

