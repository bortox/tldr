---
author: ['Marco Bonelli']
date: 1560123302
title: "cradle sql, TLDR Pages"
description: "cradle sql, Gestisci database SQL di Cradle."
categories: "common"
---
> Maggiori informazioni: <https://cradlephp.github.io/docs/3.B.-Reference-Command-Line-Tools.html#sql>.

- Ricostruisci lo schema del database:

```bash
cradle sql build
```

- Ricostruisci lo schema del database per uno specifico pacchetto:

```bash
cradle sql build nome_pacchetto
```

- Svuota l'intero database:

```bash
cradle sql flush
```

- Svuota le tabelle del database per uno specifico pacchetto:

```bash
cradle sql flush nome_pacchetto
```

- Popola le tabelle per tutti i pacchetti:

```bash
cradle sql populate
```

- Popola le tabelle per uno specifico pacchetto:

```bash
cradle sql populate nome_pacchetto
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | cradle-sql: add Italian translation. | 2019-06-10T01:35:02 | [41b3dc8a6965](https://github.com/tldr-pages/tldr/commit/41b3dc8a6965de35f6e2354aeb7d9301cfabede0)

