---
author: ['Marco Bonelli', 'Schneider']
date: 1559564381
title: "browser-sync, TLDR Pages"
description: "browser-sync, Avvia un web-server locale che si aggiorna al cambiamento dei file."
categories: "common"
---
> Maggiori informazioni: <https://browsersync.io/docs/command-line>.

- Avvia un server da una specifica directory:

```bash
browser-sync start --server percorso/a/directory --files percorso/a/directory
```

- Avvia un server da una directory locale, monitorando tutti i file CSS:

```bash
browser-sync start --server --files 'percorso/a/directory/*.css'
```

- Crea un file di configurazione:

```bash
browser-sync init
```

- Avvia bower-sync da un file di configurazione:

```bash
browser-sync start --config file_di_configurazione
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\browser-sync.md: add homepage | 2019-05-14T19:40:23 | [b8e8bd15dbcb](https://github.com/tldr-pages/tldr/commit/b8e8bd15dbcb08505e48005a19b6590cf4c790c9)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | browser-sync: add Italian translation. | 2019-01-28T19:10:19 | [e4860c103bb7](https://github.com/tldr-pages/tldr/commit/e4860c103bb7e3f9ef8781f75f13a0eaf41523e0)

