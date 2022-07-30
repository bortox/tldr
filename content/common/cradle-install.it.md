---
author: ['Marco Bonelli']
date: 1560123302
title: "cradle install"
description: "cradle install, Installa i componenti del framework Cradle per PHP."
categories: "common"
---
> Maggiori informazioni: <https://cradlephp.github.io/docs/3.B.-Reference-Command-Line-Tools.html#install>.

- Installa i componenti di Cradle (maggiori dettagli verranno richiesti all'utente):

```bash
cradle install
```

- Sovrascrivi i file forzatamente:

```bash
cradle install --force
```

- Salta l'esecuzione di migrazioni SQL:

```bash
cradle install --skip-sql
```

- Salta l'esecuzione di aggiornamenti dei pacchetti:

```bash
cradle install --skip-versioning
```

- Utilizza specifici dettagli per il database:

```bash
cradle install -h hostname -u nome_utente -p password
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | cradle-install: add Italian translation. | 2019-06-10T01:35:02 | [78d81fda46d1](https://github.com/tldr-pages/tldr/commit/78d81fda46d10884dce5e45bbd2353358f539f88)

