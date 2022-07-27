---
author: ['Marco Bonelli']
date: 1560123302
title: "csvcut, TLDR Pages"
description: "csvcut, Filtra e tronca file CSV. Come il comando Unix `cut`, ma per dati tabellari."
categories: "common"
---
> Incluso in csvkit.

> Maggiori informazioni: <https://csvkit.readthedocs.io/en/latest/scripts/csvcut.html>.

- Stampa indici e nomi di tutte le colonne:

```bash
csvcut -n dati.csv
```

- Estrai la prima e terza colonna:

```bash
csvcut -c 1,3 dati.csv
```

- Estrai tutte le colonne **eccetto** la quarta:

```bash
csvcut -C 4 dati.csv
```

- Estrai le colonne "id" e "nome di battesimo" (in quest'ordine):

```bash
csvcut -c id,"nome di battesimo" dati.csv
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | csvcut: add Italian translation. | 2019-06-10T01:35:02 | [1615b08c2dcb](https://github.com/tldr-pages/tldr/commit/1615b08c2dcb3fb1eca0d79ca0312ba8f34a10c2)

