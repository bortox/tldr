---
author: ['bl-ue', 'Carlos Vieira']
date: 1610811211
title: "docker build"
description: "docker build, Cria uma imagem a partir de um Dockerfile."
categories: "common"
---
> Mais informações: <https://docs.docker.com/engine/reference/commandline/build/>.

- Cria uma imagem docker usando o Dockerfile presente no diretório atual:

```bash
docker build .
```

- Cria uma imagem docker usando o Dockerfile de uma URL específica:

```bash
docker build github.com/creack/docker-firefox
```

- Cria uma imagem docker e cria uma tag para ela:

```bash
docker build --tag nome:tag .
```

- Não usa o cache na criação da imagem:

```bash
docker build --no-cache --tag nome:tag .
```

- Cria uma imagem docker usando um Dockerfile específico:

```bash
docker build --file Dockerfile .
```

- Cria uma imagem docker utilizando variáveis customizadas para a criação de imagens:

```bash
docker build --build-arg PROXY_DO_HTTP=http://10.20.30.2:1234 --build-arg PROXY_DO_FTP=http://40.50.60.5:4567 .
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages, MAINTAINERS: remove trailing whitespace at line ends (#5151) * multiple pages: remove trailing whitespace at the end [...] | 2021-01-16T16:33:31 | [96145696557f](https://github.com/tldr-pages/tldr/commit/96145696557f2ee2d55577cd8a617d5a1885d200)
[Carlos Vieira](mailto:3831408+caduvieira@users.noreply.github.com) | docker-build: add pt_BR translation | 2020-11-04T20:34:58 | [c57c0cb093f5](https://github.com/tldr-pages/tldr/commit/c57c0cb093f58c2a8ca981277aa019a6e14abdff)

