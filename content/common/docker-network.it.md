---
author: ['Guido Lena Cota']
date: 1618671324
title: "docker network"
description: "docker network, Crea e gestisci reti docker."
categories: "common"
---
> Maggiori informazioni: <https://docs.docker.com/engine/reference/commandline/network/>.

- Elenca le reti disponibili configurate sul docker daemon:

```bash
docker network ls
```

- Crea una rete definita da un utente:

```bash
docker network create --driver nome_del_driver nome_rete
```

- Mostra informazioni dettagliate su una lista di reti (separata da spazi):

```bash
docker network inspect nome_rete_1 nome_rete_2
```

- Connetti un container ad una rete usando il suo nome o ID:

```bash
docker network connect nome_rete nome_container|ID
```

- Disconnetti un container da una rete:

```bash
docker network disconnect nome_rete nome_container|ID
```

- Elimina le reti inutilizzate (non referenziate da alcun container):

```bash
docker network prune
```

- Elimina una lista di reti (separata da spazi) inutilizzate:

```bash
docker network rm nome_rete_1 nome_rete_2
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | docker*: add Italian translation (#5778) | 2021-04-17T16:55:24 | [eb5be8267a2d](https://github.com/tldr-pages/tldr/commit/eb5be8267a2ddd4ba4da205eb6cbd6cff38f520e)

