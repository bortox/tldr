---
author: ['Marco Bonelli', 'marchersimon']
date: 1618756407
title: "cmp, TLDR Pages"
description: "cmp, Compara due file."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/diffutils/manual/html_node/Invoking-cmp.html>.

- Trova l'indice del primo byte e della prima riga differente tra due file:

```bash
cmp file1 file2
```

- Trova ogni coppia di byte differenti ed il relativo indice:

```bash
cmp -l file1 file2
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | cmp: add link | 2021-04-18T16:33:27 | [9eb75b07f3cc](https://github.com/tldr-pages/tldr/commit/9eb75b07f3cc3af985266eb4ded57ce7ac877abc)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | cmp: add Italian translation. | 2019-06-10T01:35:02 | [a15223839318](https://github.com/tldr-pages/tldr/commit/a152238393187ed8c766b259871c0ef78c11cf09)

