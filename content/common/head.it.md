---
author: ['Dario Vladović', 'gRastello', 'marchersimon']
date: 1617292466
title: "head"
description: "head, Stampa a schermo le prime linee di un file."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/head>.

- Stampa a schermo le prime linee di un file:

```bash
head -n numero_di_linee file
```

- Stampa a schermo i primi byte di un file:

```bash
head -c numero_di_byte file
```

- Stampa a schermo tutto il file meno le ultime linee:

```bash
head -n -numero_di_linee file
```

- Stampa a schermo tutto il file meno gli ultimi byte:

```bash
head -c -numero_di_byte file
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | head: add more information link (#5583) | 2021-03-30T14:04:55 | [65067d455238](https://github.com/tldr-pages/tldr/commit/65067d4552383e7f6ff35cc471ac907505040d62)
[gRastello](mailto:gabriele.rastello@edu.unito.it) | head: add Italian translation. fixed typos | 2019-02-06T17:08:07 | [ccb7e50fe437](https://github.com/tldr-pages/tldr/commit/ccb7e50fe43736977e0f16fc5ab61210455b9fde)

