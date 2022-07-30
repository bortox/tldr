---
author: ['Carlos Vieira']
date: 1604605098
title: "docker logs"
description: "docker logs, Exibe os logs dos containers."
categories: "common"
---
> Mais informações: <https://docs.docker.com/engine/reference/commandline/logs>.

- Exibe logs de um container:

```bash
docker logs nome_do_container
```

- Exibe logs de um container e segue exibindo:

```bash
docker logs -f nome_do_container
```

- Exibe as últimas 5 linhas:

```bash
docker logs nome_do_container --tail 5
```

- Exibe logs e adiciona a informação de hora ao log:

```bash
docker logs -t nome_do_container
```

- Exibe logs até um certo ponto no tempo de execução do container (por exemplo: 23m, 10s, 2013-01-02T13:23:37):

```bash
docker logs nome_do_container --until tempo
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Carlos Vieira](mailto:3831408+caduvieira@users.noreply.github.com) | docker-logs: add pt_BR translation | 2020-11-05T20:38:18 | [a327e5547616](https://github.com/tldr-pages/tldr/commit/a327e55476160999d1daf62e518281395e4401a1)

