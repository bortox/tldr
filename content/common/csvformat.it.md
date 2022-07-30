---
author: ['Marco Bonelli']
date: 1560123302
title: "csvformat"
description: "csvformat, Converti un file CSV in un formato di output personalizzato."
categories: "common"
---
> Incluso in csvkit.

> Maggiori informazioni: <https://csvkit.readthedocs.io/en/latest/scripts/csvformat.html>.

- Converti in un file delimitato da tab (TSV):

```bash
csvformat -T dati.csv
```

- Converti i delimitatori in un carattere personalizzato:

```bash
csvformat -D "carattere_personalizzato" dati.csv
```

- Converti caratteri newline a carriage return (^M) + newline:

```bash
csvformat -M "\r\n" dati.csv
```

- Minimizza l'utilizzo delle virgolette:

```bash
csvformat -U 0 dati.csv
```

- Massimizza l'utilizzo delle virgolette:

```bash
csvformat -U 1 dati.csv
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | csvformat: add Italian translation. | 2019-06-10T01:35:02 | [e5a3dda807c3](https://github.com/tldr-pages/tldr/commit/e5a3dda807c30020ccd32515304799f3fb55161e)

