---
author: ['Guido Lena Cota']
date: 1618671324
title: "docker image"
description: "docker image, Gestisci immagini Docker."
categories: "common"
---
> Vedi anche `docker build`, `docker import` e `docker pull`.

> Maggiori informazioni: <https://docs.docker.com/engine/reference/commandline/image/>.

- Elenca tutte le immagini Docker locali:

```bash
docker image ls
```

- Elimina le immagini Docker locali inutilizzate:

```bash
docker image prune
```

- Cancella tutte le immagini inutilizzate (non solo quelle sprovviste di tag):

```bash
docker image prune --all
```

- Mostra la cronologia di un'immagine Docker locale:

```bash
docker image history immagine
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | docker*: add Italian translation (#5778) | 2021-04-17T16:55:24 | [eb5be8267a2d](https://github.com/tldr-pages/tldr/commit/eb5be8267a2ddd4ba4da205eb6cbd6cff38f520e)

