---
author: ['Marco Bonelli', 'marchersimon']
date: 1618756407
title: "column"
description: "column, Formatta standard input o un file in più colonne."
categories: "common"
---
> Le colonne sono riempite prima delle righe; il separatore predefinito è lo spazio.

> Maggiori informazioni: <https://manned.org/column>.

- Formatta l'output per uno schermo largo 30 caratteri:

```bash
printf "intestazione1 intestazione2\nbar foo\n" | column --output-width 30
```

- Specifica un diverso separatore di colonna (e.g. "," per csv) (il predefinito è lo spazio):

```bash
printf "intestazione1 intestazione2\nbar foo\n" | column --separator ,
```

- Separa colonne ed allinea automaticamente in un formato tabulare:

```bash
printf "intestazione1 intestazione2\nbar foo\n" | column --table
```

- Riempi le righe prima delle colonne:

```bash
printf "intestazione1\nbar\nfoobar\n" | column --output-width 30 --fillrows
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | column: add link | 2021-04-18T16:33:27 | [010ec036106c](https://github.com/tldr-pages/tldr/commit/010ec036106ce5c68aa2a9416ad819d1014178da)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | column: add Italian translation. | 2019-06-10T01:35:02 | [b4a0517f7094](https://github.com/tldr-pages/tldr/commit/b4a0517f70942c5eb2bcc7b876e2708dd5bebf93)

