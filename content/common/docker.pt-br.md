---
author: ['Rui Alves', 'Gustavo Cavalieri Fernandes', 'Marco Bonelli']
date: 1633457023
title: "docker"
description: "docker, Gerenciador de containers e imagens Docker."
categories: "common"
---
> Alguns subcomandos como `docker run` tem sua própia documentação de uso.

> Mais informações: <https://docs.docker.com/engine/reference/commandline/cli/>.

- Listar os containers Docker que se encontram em execução:

```bash
docker ps
```

- Listar todos os containers Docker:

```bash
docker ps -a
```

- Inicializar um container com um nome personalizado a partir de uma imagem:

```bash
docker run --name nome_container imagem
```

- Começar ou parar um container existente:

```bash
docker start|stop nome_container
```

- Extrair uma imagem a partir de um Docker Registry:

```bash
docker pull imagem
```

- Abrir um terminal dentro de um container em execução:

```bash
docker exec -it nome_container sh
```

- Remover um container parado:

```bash
docker rm nome_container
```

- Obter e acompanhar o histórico de um container:

```bash
docker logs -f nome_container
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gustavo Cavalieri Fernandes](mailto:gugacavalieri@gmail.com) | *: mention subcommands in pt_BR translation (#6798) | 2021-10-05T20:03:43 | [ed5274772bd2](https://github.com/tldr-pages/tldr/commit/ed5274772bd2b09eb465abfd4e132f47048783a2)
[Marco Bonelli](mailto:marco@mebeim.net) | multiple pages (pt_BR): add missing trailing newline. | 2019-10-25T14:27:07 | [0d3209adbbbf](https://github.com/tldr-pages/tldr/commit/0d3209adbbbf41b9672a1bed97c13e7081c269f2)
[Rui Alves](mailto:up201606746@fe.up.pt) | docker: add pt_BR translation (#3395) | 2019-10-18T18:27:32 | [0e7f5f81639a](https://github.com/tldr-pages/tldr/commit/0e7f5f81639a16b6e0b880c913433bf428b689dd)

