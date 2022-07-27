---
author: ['Marco Bonelli', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "dircolors, TLDR Pages"
description: "dircolors, Stampa comandi necessari per settare la variabile d'ambiente LS_COLOR per stilizzare `ls`, `dir`, etc."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/dircolors>.

- Stampa i comandi per settare LS_COLOR con i colori predefiniti:

```bash
dircolors
```

- Stampa i comandi per settare LS_COLOR con i colori definiti in un file:

```bash
dircolors file
```

- Stampa comandi per la Bourne shell:

```bash
dircolors --bourne-shell
```

- Stampa comandi per la C shell:

```bash
dircolors --c-shell
```

- Mostra i colori predefiniti per diversi tipi di file ed estensioni:

```bash
dircolors --print-data
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | dircolors: add more information link (#5558) | 2021-03-30T12:48:19 | [51ed8c8760f2](https://github.com/tldr-pages/tldr/commit/51ed8c8760f275bb771862d7d99aa74c30a87a89)
[Marco Bonelli](mailto:marco@mebeim.net) | dircolors: add Italian translation. | 2019-07-21T01:59:28 | [b39c8b83374b](https://github.com/tldr-pages/tldr/commit/b39c8b83374b1dde74897f521e56871dc73932ec)

