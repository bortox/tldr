---
author: ['bl-ue', 'marchersimon', 'Marco Bonelli']
date: 1659075216
title: "batch, TLDR Pages"
description: "batch, Esegui comandi nel futuro quando il carico di lavoro del sistema lo permette."
categories: "common"
---
> Il servizio atd (o atrun) deve essere attivo per eseguire i comandi.

> Maggiori informazioni: <https://manned.org/batch>.

- Esegui i comandi inseriti standard input (premere `Ctrl + D` dopo aver inserito i comandi):

```bash
batch
```

- Esegui un comando da standard input:

```bash
echo "./mio_script.sh" | batch
```

- Esegui comandi contenuti in un dato file:

```bash
batch -f percorso/al/file
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | at, atq, atrm, batch: add more information link (#5640) | 2021-03-30T21:01:46 | [f1da7db16065](https://github.com/tldr-pages/tldr/commit/f1da7db160655446057cf641b5339d2e9273bb7a)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | batch: add Italian translation. | 2019-01-28T19:10:19 | [ff2d65426f2a](https://github.com/tldr-pages/tldr/commit/ff2d65426f2a10909304504343b424c4a8b5dfbb)

