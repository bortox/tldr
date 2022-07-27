---
author: ['Marco Bonelli']
date: 1560123302
title: "awk, TLDR Pages"
description: "awk, Un versatile linguaggio di programmazione per elaborare file."
categories: "common"
---
> Maggiori informazioni: <https://github.com/onetrueawk/awk>.

- Stampa la quinta colonna (field) in un file di linee separate da spazi:

```bash
awk '{print $5}' nome_file
```

- Stampa la seconda colonna delle linee contenenti "qualcosa":

```bash
awk '/qualcosa/ {print $2}' nome_file
```

- Stampa l'ultima colonna di ogni linea di un file, utilizzando la virgola (invece dello spazio) come separatore di colonne:

```bash
awk -F ',' '{print $NF}' nome_file
```

- Somma i valori nella prima colonna di un file e stampa il totale:

```bash
awk '{s+=$1} END {print s}' nome_file
```

- Somma i valori nella prima colonna e stampali seguiti dal totale:

```bash
awk '{s+=$1; print $1} END {print "--------"; print s}' nome_file
```

- Stampa una liena ogni tre iniziando dalla prima:

```bash
awk 'NR%3==1' nome_file
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | awk: add Italian translation. | 2019-01-28T19:10:19 | [411d4e38a7bc](https://github.com/tldr-pages/tldr/commit/411d4e38a7bc3f2d636d606754880c0b13d56583)

