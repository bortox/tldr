---
author: ['Franz', 'Marco Bonelli']
date: 1633438869
title: "docker"
description: "docker, Gestisci container ed immagini Docker."
categories: "common"
---
> Alcuni comandi aggiuntivi, come `docker run`, hanno la propria documentazione.

> Maggiori informazioni: <https://docs.docker.com/engine/reference/commandline/cli/>.

- Elenca i container Docker attualmente in esecuzione:

```bash
docker ps
```

- Elenca tutti i container Docker (in esecuzione e arrestati):

```bash
docker ps -a
```

- Avvia un container da una immagine, con un nome personalizzato:

```bash
docker run --name nome_container immagine
```

- Avvia o arresta un container esistente:

```bash
docker start|stop nome_container
```

- Scarica (pull) un'immagine dal Docker registry:

```bash
docker pull image
```

- Avvia una shell all'interno di un container in esecuzione:

```bash
docker exec -it nome_container sh
```

- Rimuovi un container arrestato:

```bash
docker rm nome_container
```

- Ottieni e visualizza i log di un container:

```bash
docker logs -f nome_container
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Franz](mailto:franz.f1032@gmail.com) | *: mention subcommands in Italian translation (#6804) | 2021-10-05T15:01:09 | [e13e67b1711e](https://github.com/tldr-pages/tldr/commit/e13e67b1711e4112cca0cc4d07521c0cf901290c)
[Marco Bonelli](mailto:marco@mebeim.net) | docker: add Italian translation. | 2019-10-05T15:25:51 | [34dd40036212](https://github.com/tldr-pages/tldr/commit/34dd40036212518a35ae49f9910eef3b230f5bed)

