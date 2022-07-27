---
author: ['Marco Bonelli']
date: 1560123302
title: "convmv, TLDR Pages"
description: "convmv, Coversione dei nomi dei file (NON del contenuto) da un encoding ad un altro."
categories: "common"
---
> Maggiori informazioni: <https://www.j3e.de/linux/convmv/man/>.

- Controlla la conversione di encoding (non rinomina realmente il file):

```bash
convmv -f encoding_originale -t encoding_finale file_input
```

- Converti l'encoding del nome di un file e rinominalo utilizzando il nuovo encoding:

```bash
convmv -f encoding_originale -t encoding_finale --notest file_input
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | convmv: add Italian translation. | 2019-06-10T01:35:02 | [de242bc13f79](https://github.com/tldr-pages/tldr/commit/de242bc13f790f3d403d6dcddff1ca0dff861081)

