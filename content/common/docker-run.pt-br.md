---
author: ['Carlos Vieira', 'bl-ue']
date: 1610811211
title: "docker run, TLDR Pages"
description: "docker run, Executa um comando em um novo container Docker."
categories: "common"
---
> Mais informações: <https://docs.docker.com/engine/reference/commandline/run/>.

- Executa um comando em um novo container de uma imagem tagueada:

```bash
docker run imagem:tag comando
```

- Executa um comando em um novo container em background e exibe o ID:

```bash
docker run -d image command
```

- Executa um comando em um novo container que será removido após a execução em um modo interativo e com um terminal TTY:

```bash
docker run --rm -it image command
```

- Executa um comando em um novo container com variáveis de ambiente:

```bash
docker run -e 'variável=valor' -e variável imagem comando
```

- Executa um comando em um novo container montando volumes nos caminhos específicos:

```bash
docker run -v caminho/no/host_local:caminho/no/container imagem comando
```

- Executa um comando em um novo container e abre as portas para acesso:

```bash
docker run -p porta_do_host_local:porta_do_container imagem comando
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages, MAINTAINERS: remove trailing whitespace at line ends (#5151) * multiple pages: remove trailing whitespace at the end [...] | 2021-01-16T16:33:31 | [96145696557f](https://github.com/tldr-pages/tldr/commit/96145696557f2ee2d55577cd8a617d5a1885d200)
[Carlos Vieira](mailto:3831408+caduvieira@users.noreply.github.com) | docker-run: add pt_BR translation | 2020-11-04T20:34:58 | [eff366b5416d](https://github.com/tldr-pages/tldr/commit/eff366b5416deb9f1844ca3d62b7c3208b29e324)

