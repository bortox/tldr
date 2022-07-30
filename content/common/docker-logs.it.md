---
author: ['Guido Lena Cota']
date: 1618671324
title: "docker logs"
description: "docker logs, Mostra i log di un container."
categories: "common"
---
> Maggiori informazioni: <https://docs.docker.com/engine/reference/commandline/logs>.

- Mostra i log di un container:

```bash
docker logs nome_container
```

- Segui i log di un container:

```bash
docker logs -f nome_container
```

- Mostra le ultime 5 righe:

```bash
docker logs nome_container --tail 5
```

- Mostra i log mettendo un timestamp in coda:

```bash
docker logs -t nome_container
```

- Mostra i log avvenuti prima di un dato momento nell'esecuzione del container (ad esempio, 23m, 10s, 2013-01-02T13:23:37):

```bash
docker logs nome_container --until momento
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | docker*: add Italian translation (#5778) | 2021-04-17T16:55:24 | [eb5be8267a2d](https://github.com/tldr-pages/tldr/commit/eb5be8267a2ddd4ba4da205eb6cbd6cff38f520e)

