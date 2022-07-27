---
author: ['caduvieira']
date: 1633698984
title: "docker stats, TLDR Pages"
description: "docker stats, Exibe estatísticas dinâmicas de uso de recursos dos containers."
categories: "common"
---
> Mais informações: <https://docs.docker.com/engine/reference/commandline/stats/>.

- Exibe estatísticas atualizadas de todos os containers em execução:

```bash
docker stats
```

- Exibe estatísticas atualizadas de uma lista separada por espaço dos containers:

```bash
docker stats nome_do_container
```

- Altera o formato das colunas para exibir o uso da CPU em porcentagem:

```bash
docker stats --format ".Name:\t.CPUPerc"
```

- Exibe estatísticas para todos os containers (tanto em execução como parados):

```bash
docker stats --all
```

- Desabilita estatísticas atualizadas e só exibe o status naquele momento:

```bash
docker stats --no-stream
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[caduvieira](mailto:3831408+caduvieira@users.noreply.github.com) | docker-cp, docker-rmi, docker-stats: add pt_BR translation (#6783) | 2021-10-08T15:16:24 | [37b005c3623e](https://github.com/tldr-pages/tldr/commit/37b005c3623ec0332bbc69dd41a251087f98d55c)

