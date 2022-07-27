---
author: ['Marco Bonelli']
date: 1570281951
title: "enca, TLDR Pages"
description: "enca, Rileva e converti l'encoding di file di testo."
categories: "common"
---
> Maggiori informazioni: <https://github.com/nijel/enca>.

- Rileva l'encoding di uno o più file in base alla locale di sistema:

```bash
enca file1 file2 ...
```

- Rileva l'encoding specificando un linguaggio nel formato di locale POSIX/C (e.g. zh_CN, en_US):

```bash
enca -L linguaggio file1 file2 ...
```

- Converti file ad uno specifico encoding:

```bash
enca -L linguaggio -x encoding file1 file2 ...
```

- Crea una copia di un file esistente utilizznado un encoding diverso:

```bash
enca -L linguaggio -x encoding_finale < file_originale > nuovo_file
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | enca: add Italian translation. | 2019-10-05T15:25:51 | [43fa5d6c2ae5](https://github.com/tldr-pages/tldr/commit/43fa5d6c2ae59d5c26566f61050b9f108ade62e9)

