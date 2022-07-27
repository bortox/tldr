---
author: ['Marco Bonelli', 'marchersimon']
date: 1618756407
title: "bc, TLDR Pages"
description: "bc, Calcolatore."
categories: "common"
---
> Maggiori informazioni: <https://manned.org/bc>.

- Esegui in modalità interattiva utilizzando la libreria math della standard library:

```bash
bc -l
```

- Calcola il risultato di un'espressione:

```bash
bc <<< "(1 + 2) * 2 ^ 2"
```

- Calcola un'espressione forzando il numero di decimali usati a 10:

```bash
bc <<< "scale=10; 5 / 3"
```

- Calcola un'espressione con seno e coseno utilizzando mathlib:

```bash
bc -l <<< "s(1) + c(1)"
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | bc: add link | 2021-04-18T16:33:27 | [2c7348ccdd6b](https://github.com/tldr-pages/tldr/commit/2c7348ccdd6bc47e877d760a180c8cd685d9a4e8)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | bc: add Italian translation. | 2019-01-28T19:10:19 | [ab53bc8a79e8](https://github.com/tldr-pages/tldr/commit/ab53bc8a79e84b771fef3f71c7fb6606b30461fd)

