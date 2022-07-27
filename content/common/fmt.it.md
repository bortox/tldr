---
author: ['gRastello', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "fmt, TLDR Pages"
description: "fmt, Riformatta i paragrafi di un file di testo unendoli e limitando la larghezza delle righe a un dato numero di caratteri (di default 75)."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/fmt>.

- Riformatta un file:

```bash
fmt percorso/al/file
```

- Riformatta un file producendo linee di (al massimo) `n` caratteri:

```bash
fmt -w n percorso/al/file
```

- Riformatta un file senza unire assieme le linee più corte della data larghezza:

```bash
fmt -s percorso/al/file
```

- Riformatta un file usando una spaziatura uniforme (1 spazio tra due parole e 2 spazi tra due paragrafi):

```bash
fmt -u percorso/al/file
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | fmt: add link (#5578) | 2021-03-30T08:56:16 | [30b4f26add36](https://github.com/tldr-pages/tldr/commit/30b4f26add3636e47ae11fd0f812671dacf2ab7f)
[gRastello](mailto:gabriele.rastello@edu.unito.it) | fmt: add Italian translation | 2019-02-10T00:22:44 | [5bdea20ff370](https://github.com/tldr-pages/tldr/commit/5bdea20ff3709b14a95b242a60c22ab15a32f183)

