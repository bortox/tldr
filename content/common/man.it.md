---
author: ['Noy', 'mxmxyz', 'Patrice Denis', 'bl-ue']
date: 1631536931
title: "man, TLDR Pages"
description: "man, Formatta e mostra pagine manuale."
categories: "common"
---
> Maggiori informazioni: <https://www.man7.org/linux/man-pages/man1/man.1.html>.

- Mostra la pagina di manuale di un comando:

```bash
man comando
```

- Mostra la pagina di manuale per un comando dalla sezione 7:

```bash
man 7 comando
```

- Mostra il percorso in cui vengono cercate le pagine:

```bash
man --path
```

- Mostra la posizione di una pagina invece che la pagina stessa:

```bash
man -w comando
```

- Cerca pagine di manuale che contengano una certa stringa:

```bash
man -k ricerca
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Noy](mailto:nbaltunian@gmail.com) | man: correct syntax (#6505) | 2021-09-13T14:42:11 | [efeee14594da](https://github.com/tldr-pages/tldr/commit/efeee14594dab9cc5dd082f03a53dbfa83298fb0)
[Patrice Denis](mailto:patrice.denis@gmail.com) | man: add more info link and --locale example (#5504) | 2021-03-25T22:54:01 | [b431ae33f75d](https://github.com/tldr-pages/tldr/commit/b431ae33f75dbfc3d554f9e611b4f1301ce12885)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages, MAINTAINERS: remove trailing whitespace at line ends (#5151) * multiple pages: remove trailing whitespace at the end [...] | 2021-01-16T16:33:31 | [96145696557f](https://github.com/tldr-pages/tldr/commit/96145696557f2ee2d55577cd8a617d5a1885d200)
[mxmxyz](mailto:mxmxyzgxyzt@gmail.com) | 6 translations to italian | 2020-09-09T02:42:53 | [ae3ba00236f1](https://github.com/tldr-pages/tldr/commit/ae3ba00236f1e305ae16d0a317d345bffe88c857)

