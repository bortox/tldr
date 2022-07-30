---
author: ['Marco Bonelli']
date: 1560123302
title: "csvstat"
description: "csvstat, Stampa statistiche descrittive per tutte le colonne di un file CSV."
categories: "common"
---
> Incluso in csvkit.

> Maggiori informazioni: <https://csvkit.readthedocs.io/en/latest/scripts/csvstat.html>.

- Mostra tutte le statistiche per tutte le colonne:

```bash
csvstat dati.csv
```

- Mostra tutte le statistiche per le colonne 2 e 4:

```bash
csvstat -c 2,4 dati.csv
```

- Mostra la somma per tutte le colonne:

```bash
csvstat --sum dati.csv
```

- Mostra la lunghezza massima dei valori della colonna 3:

```bash
csvstat -c 3 --len dati.csv
```

- Mostra il numedo di valori unici nella colonna "nome":

```bash
csvstat -c nome --unique dati.csv
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | csvstat: add Italian translation. | 2019-06-10T01:35:02 | [1d1651f6a4f6](https://github.com/tldr-pages/tldr/commit/1d1651f6a4f6b53be7e7e950ab53ab03d532744c)

