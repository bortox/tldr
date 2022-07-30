---
author: ['Schneider', 'lucas schneider', 'Marco Bonelli']
date: 1610111394
title: "bup"
description: "bup, Sistema di backup basato sul formato dei packfile Git, fornendo salvataggi incrementali veloci e deduplicazione globale."
categories: "common"
---
> Maggiori informazioni: <https://github.com/bup/bup>.

- Inizializza una repository di backup nella directory locale specificata:

```bash
bup -d percorso/a/repository init
```

- Prepara una certa cartella prima di fare un backup:

```bash
bup -d percorso/a/repository index percorso/a/directory
```

- Esegui il backup di una cartella in una repository locale:

```bash
bup -d percorso/a/repository save -n nome_backup percorso/a/directory
```

- Elenca i di backup attualmente nella repository:

```bash
bup -d percorso/a/repository ls
```

- Ripristina uno specifico backup in una determinata cartella locale:

```bash
bup -d percorso/a/repository restore -C percorso/a/destinazione nome_backup
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[lucas schneider](mailto:casdpa@gmail.com) | rename git to Git | 2021-01-08T14:09:54 | [eef3712fc3a6](https://github.com/tldr-pages/tldr/commit/eef3712fc3a6a3774384b2e4ed934583c8349d75)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\bup.md: add homepage | 2019-05-14T19:40:23 | [49cfbdbe58cd](https://github.com/tldr-pages/tldr/commit/49cfbdbe58cde530dd8b9a14175b922d4a220644)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | bup: add Italian translation. | 2019-01-28T19:10:19 | [57c8899ee3f9](https://github.com/tldr-pages/tldr/commit/57c8899ee3f9c0263d47cb50ff404ff385dc39fc)

