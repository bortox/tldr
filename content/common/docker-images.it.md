---
author: ['Marco Bonelli']
date: 1570281951
title: "docker images, TLDR Pages"
description: "docker images, Gestisci immagini Docker."
categories: "common"
---
> Maggiori informazioni: <https://docs.docker.com/engine/reference/commandline/images/>.

- Elenca tutte le immagini Docker:

```bash
docker images
```

- Elenca tutte le immagini Docker incluse quelle intermedie:

```bash
docker images -a
```

- Elenca in modalità silenziosa (solo gli ID numerici):

```bash
docker images -q
```

- Elenca tutte le immagini Docker che non sono usate da alcun container:

```bash
docker images --filter dangling=true
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | docker-image: add Italian translation. | 2019-10-05T15:25:51 | [26120f3a4074](https://github.com/tldr-pages/tldr/commit/26120f3a4074a67eaec582a45d03e438f90ed7a4)

