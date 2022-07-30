---
author: ['Schneider', 'Marco Bonelli']
date: 1559564381
title: "autoflake"
description: "autoflake, Uno strumento per rimuovere import e variabili inutilizzati da codice Python."
categories: "common"
---
> Maggiori informazioni: <https://github.com/myint/autoflake>.

- Rimuovi le variabili inutilizzate da un file e mostra la differenza:

```bash
autoflake --remove-unused-variables file.py
```

- Rimuovi gli import inutilizzati da multipli file mostrando le differenze:

```bash
autoflake --remove-all-unused-imports file1.py file2.py file3.py
```

- Rimuovi le variabili inutilizzate da un file, sovrascrivendolo:

```bash
autoflake --remove-unused-variables --in-place file.py
```

- Rimuovi le variabili inutilizzate da tutti i file in una cartella, ricorsivamente e sovrascrivendoli:

```bash
autoflake --remove-unused-variables --in-place --recursive percorso/a/cartella
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\autoflake.md:add homepage | 2019-05-14T19:40:23 | [060b9cbe1ff1](https://github.com/tldr-pages/tldr/commit/060b9cbe1ff179a22fb2b9b62bf3d245c240f71f)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | autoflake: add Italian translation. | 2019-01-28T19:10:19 | [8c5f5a899750](https://github.com/tldr-pages/tldr/commit/8c5f5a899750e0556ec171ddd1e77f0db5ffdca5)

