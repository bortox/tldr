---
author: ['Guido Lena Cota']
date: 1618671324
title: "docker build"
description: "docker build, Crea un'immagine a partire da un Dockerfile. La creazione di un'immagine docker è chiamata build."
categories: "common"
---
> Maggiori informazioni: <https://docs.docker.com/engine/reference/commandline/build/>.

- Crea un'immagine docker usando il Dockerfile nella directory corrente:

```bash
docker build .
```

- Crea un'immagine docker usando il Dockerfile disponibile a un dato URL:

```bash
docker build github.com/creack/docker-firefox
```

- Crea e tagga un'immagine docker:

```bash
docker build --tag nome:tag .
```

- Non usare la cache per la creazione di un'immagine docker:

```bash
docker build --no-cache --tag nome:tag .
```

- Crea un'immagine docker usando un dato Dockerfile:

```bash
docker build --file Dockerfile .
```

- Crea un'immagine docker usando variabili fornite in fase di build:

```bash
docker build --build-arg HTTP_PROXY=http://10.20.30.2:1234 --build-arg FTP_PROXY=http://40.50.60.5:4567 .
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | docker*: add Italian translation (#5778) | 2021-04-17T16:55:24 | [eb5be8267a2d](https://github.com/tldr-pages/tldr/commit/eb5be8267a2ddd4ba4da205eb6cbd6cff38f520e)

