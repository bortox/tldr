---
author: ['Marco Bonelli', 'marchersimon']
date: 1618756407
title: "ar, TLDR Pages"
description: "ar, Crea, modifica ed estrai da archivi (`.a`, `.so`, `.o`)."
categories: "common"
---
> Maggiori informazioni: <https://manned.org/ar>.

- Estrai tutti i membri da un archivio:

```bash
ar -x libfoo.a
```

- Lista tutti i membri di un archivio:

```bash
ar -t libfoo.a
```

- Sostituisci o aggiungi file ad un archvio:

```bash
ar -r libfoo.a foo.o bar.o baz.o
```

- Inserisci o sostituisci un indice in un archivio (equivalente ad usare `ranlib`):

```bash
ar -s libfoo.a
```

- Crea un archivio con dei file creando anche il relativo indice:

```bash
ar -rs libfoo.a foo.o bar.o baz.o
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Apply suggestions from code review Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-04-18T16:33:27 | [3c2cf700535c](https://github.com/tldr-pages/tldr/commit/3c2cf700535c96240fc4832e5c1e117c6e4b696d)
[marchersimon](mailto:marchersimon@zohomail.eu) | ar: add link | 2021-04-18T16:33:27 | [bc1219f3c90d](https://github.com/tldr-pages/tldr/commit/bc1219f3c90dc2328626e04ab6496ddd8f0405d3)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | ar: add Italian translation. | 2019-01-28T19:10:19 | [e7053c20b2aa](https://github.com/tldr-pages/tldr/commit/e7053c20b2aa82e8990fe5c364b6ea01b342f5e0)

