---
author: ['Marco Bonelli']
date: 1570281951
title: "ect"
description: "ect, Efficiente Tool di Compressione (o ECT) è un ottimizzatore di file scritto in C++. Supporta file PNG, JPEG, GZIP e ZIP."
categories: "common"
---
> Maggiori informazioni: <https://github.com/fhanau/Efficient-Compression-Tool>.

- Comprimi un file:

```bash
ect file.png
```

- Comprimi un file con il massimo livello di compressione utilizzanto più thread:

```bash
ect -9 --mt-deflate file.png
```

- Comprimi tutti i file in una directory ricorsivamente, mantenendo la data di modifica originale:

```bash
ect -keep -recurse percorso/a/directory
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | ect: add Italian translation. | 2019-10-05T15:25:51 | [1a9fd44f414e](https://github.com/tldr-pages/tldr/commit/1a9fd44f414ecea93f7354ce74e86bae8fe0ba9b)

