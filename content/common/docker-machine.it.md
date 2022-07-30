---
author: ['Marco Bonelli']
date: 1570281951
title: "docker-machine"
description: "docker-machine, Crea e gestisci macchine che utilizzano Docker."
categories: "common"
---
> Maggiori informazioni: <https://docs.docker.com/machine/reference/>.

- Elenca macchine Docker in esecuzione:

```bash
docker-machine ls
```

- Crea una nuova macchina Docker con uno specifico nome:

```bash
docker-machine create nome
```

- Mostra lo stato di una macchina:

```bash
docker-machine status nome
```

- Avvia una macchina:

```bash
docker-machine start nome
```

- Arresta una macchina:

```bash
docker-machine stop nome
```

- Ispeziona le informazioni su di una macchina:

```bash
docker-machine inspect nome
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | docker-machine: add Italian translation. | 2019-10-05T15:25:51 | [da0620d73c95](https://github.com/tldr-pages/tldr/commit/da0620d73c95c28b1435701adfe89e8e6818ebb7)

