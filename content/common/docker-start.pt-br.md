---
author: ['Carlos Vieira', 'Lucas Gabriel Schneider', 'bl-ue']
date: 1612127760
title: "docker start, TLDR Pages"
description: "docker start, Inicia um ou mais containers parados."
categories: "common"
---
> Mais informações: <https://docs.docker.com/engine/reference/commandline/start/>.

- Exibe a ajuda:

```bash
docker start
```

- Inicia um container docker:

```bash
docker start container
```

- Inicia um container, atachando ao terminal os sinais stdout e stderr e outros sinais:

```bash
docker start --attach container
```

- Inicia um ou mais containers com ID separados por espaço:

```bash
docker start container(s)
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: trim trailing whitespace (#5213) | 2021-01-31T22:16:00 | [d679ad10161d](https://github.com/tldr-pages/tldr/commit/d679ad10161dd1fe7e0dd2a62358869df2a32080)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages, MAINTAINERS: remove trailing whitespace at line ends (#5151) * multiple pages: remove trailing whitespace at the end [...] | 2021-01-16T16:33:31 | [96145696557f](https://github.com/tldr-pages/tldr/commit/96145696557f2ee2d55577cd8a617d5a1885d200)
[Carlos Vieira](mailto:3831408+caduvieira@users.noreply.github.com) | docker-start: add pt_BR translation | 2020-11-04T20:34:58 | [ec070b624279](https://github.com/tldr-pages/tldr/commit/ec070b624279f65c571b2b7c1ae4fab4a86170f5)

