---
author: ['Marco Bonelli']
date: 1560123302
title: "csvsort"
description: "csvsort, Ordina le righe di di file CSV."
categories: "common"
---
> Incluso in csvkit.

> Maggiori informazioni: <https://csvkit.readthedocs.io/en/latest/scripts/csvsort.html>.

- Ordina un file CSV secondo la colonna 9:

```bash
csvsort -c 9 data.csv
```

- Ordina un file CSV secondo la colonna "nome" in ordine decrescente:

```bash
csvsort -r -c nome data.csv
```

- Ordina un file CSV secondo la colonna 2 e secondo la 4:

```bash
csvsort -c 2,4 data.csv
```

- Ordina un file CSV senza inferire il tipo dei dati:

```bash
csvsort --no-inference -c colonne data.csv
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | csvsort: add Italian translation. | 2019-06-10T01:35:02 | [4736a0e9eddd](https://github.com/tldr-pages/tldr/commit/4736a0e9eddde740ba67b0837b59b74afa9f9d3f)

