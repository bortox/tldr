---
author: ['bl-ue']
date: 1615231858
title: "docker container, TLDR Pages"
description: "docker container, Gestisci container Docker."
categories: "common"
---
> Maggiori informazioni: <https://docs.docker.com/engine/reference/commandline/container/>.

- Elenca i container Docker attualmente in esecuzione:

```bash
docker container ls
```

- Avvia uno o più container fermi:

```bash
docker container start nome_container1 nome_container2
```

- Termina uno o più container in esecuzione:

```bash
docker container kill nome_container
```

- Ferma uno o più container in esecuzione:

```bash
docker container stop nome_container
```

- Sospendi tutti i processi dentro uno o più container:

```bash
docker container pause nome_container
```

- Mostra informazioni dettagliate su uno o più container:

```bash
docker container inspect nome_container
```

- Esporta il filesystem di un container come archivio tar:

```bash
docker container export nome_container
```

- Crea una nuova immagine dai cambiamenti di un container:

```bash
docker container commit nome_container
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | docker-container: sync translations with PR #5067 (#5356) | 2021-03-08T20:30:58 | [a8b4d5f55b2d](https://github.com/tldr-pages/tldr/commit/a8b4d5f55b2d93890e414c9c2e83d06f6939bcda)

