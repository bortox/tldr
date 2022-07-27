---
author: ['Locour', 'stefanyramos', 'lincc']
date: 1643487459
title: "docker-compose, TLDR Pages"
description: "docker-compose, Executa e gerencia multi-containers de aplicações Docker"
categories: "common"
---
> Mais informações: <https://docs.docker.com/compose/reference/>.

- Lista todos os containers em execução:

```bash
docker-compose ps
```

- Cria e inicia todos os containers em segundo plano usando um arquivo `docker-compose.yml` do seu diretório atual:

```bash
docker-compose up -d
```

- Inicia todos os containers. Se necessário, realiza um rebuild:

```bash
docker-compose up --build
```

- Inicia todos os containers que estão usando um arquivo compose alternativo:

```bash
docker-compose --file caminho/para/arquivo up
```

- Encerra todos os containers em execução:

```bash
docker-compose stop
```

- Encerra e remove todos os containers, networks, imagens e volumes:

```bash
docker-compose down --rmi all --volumes
```

- Segue os logs de todos os containers:

```bash
docker-compose logs --follow
```

- Segue os logs de um container específico

```bash
docker-compose logs --follow nome_container
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Locour](mailto:Locour@users.noreply.github.com) | docker-compose: add German translation (#6978) | 2021-10-13T19:23:45 | [9e781d59bed6](https://github.com/tldr-pages/tldr/commit/9e781d59bed60863bbf0de866c5f181d8622514e)
[stefanyramos](mailto:40060993+stefanyramos@users.noreply.github.com) | docker-compose: add pt_BR translation (#6886) | 2021-10-10T17:05:48 | [1e1f4421f3ef](https://github.com/tldr-pages/tldr/commit/1e1f4421f3efab60e07343d0d82e8a37578913e7)

