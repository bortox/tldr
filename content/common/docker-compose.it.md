---
author: ['Locour', 'Marco Bonelli', 'Guido Lena Cota']
date: 1634145825
title: "docker-compose, TLDR Pages"
description: "docker-compose, Esegui e gestisci applicazioni Docker composte da più container."
categories: "common"
---
> Maggiori informazioni: <https://docs.docker.com/compose/reference/>.

- Elenca i container in esecuzione:

```bash
docker-compose ps
```

- Crea ed avvia tutti i container in background utilizzando il file `docker-compose.yml` nella directory corrente:

```bash
docker-compose up -d
```

- Avvia tutti i container, buildandoli di nuovo se necessario:

```bash
docker-compose up --build
```

- Avvia tutti i container utilizzando un file compose alternativo:

```bash
docker-compose --file percorso/a/file up
```

- Ferma tutti i container in esecuzione:

```bash
docker-compose stop
```

- Ferma e rimuovi tutti i container, reti, immagini e volumi:

```bash
docker-compose down
```

- Segui i log di tutti i container:

```bash
docker-compose logs --follow
```

- Segui i log di un container specifico:

```bash
docker-compose logs --follow nome_container
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Locour](mailto:Locour@users.noreply.github.com) | docker-compose: add German translation (#6978) | 2021-10-13T19:23:45 | [9e781d59bed6](https://github.com/tldr-pages/tldr/commit/9e781d59bed60863bbf0de866c5f181d8622514e)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | docker*: add Italian translation (#5778) | 2021-04-17T16:55:24 | [eb5be8267a2d](https://github.com/tldr-pages/tldr/commit/eb5be8267a2ddd4ba4da205eb6cbd6cff38f520e)
[Marco Bonelli](mailto:marco@mebeim.net) | docker-compose: add Italian translation. | 2019-07-21T01:59:28 | [0cc11c687bef](https://github.com/tldr-pages/tldr/commit/0cc11c687bef486e688a0e46484e4bc7e9d3d1cd)

