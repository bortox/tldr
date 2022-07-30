---
author: ['Dario Vladović', 'Alessio', 'gRastello']
date: 1617292466
title: "mv"
description: "mv, Sposta o rinomina file e directory."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/mv>.

- Sposta file:

```bash
mv sorgente destinazione
```

- Sposta file senza chiedere conferma prima di sovrascrivere file esistenti:

```bash
mv -f sorgente destinazione
```

- Sposta file interattivamente, chiedendo conferma prima di sovrascrivere file esistenti:

```bash
mv -i sorgente destinazione
```

- Sposta file senza sovrascrivere file esistenti:

```bash
mv -n sorgente destinazione
```

- Sposta file in modità verbosa, mostrando a schermo ogni file che viene spostato:

```bash
mv -v sorgente destinazione
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[Alessio](mailto:25589202+tomadojuice@users.noreply.github.com) | mv: add more information link (#5542) | 2021-03-29T20:24:45 | [45ff3b27a290](https://github.com/tldr-pages/tldr/commit/45ff3b27a290a760ee43340226e4e85e2091dbfc)
[gRastello](mailto:gabriele.rastello@edu.unito.it) | mv: add Italian translation. fixed typos | 2019-02-06T17:08:07 | [d78f25a95092](https://github.com/tldr-pages/tldr/commit/d78f25a950922b7c414c28d630dcc1e364fcabb1)

