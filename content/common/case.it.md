---
author: ['Marco Bonelli', 'marchersimon']
date: 1618756407
title: "case, TLDR Pages"
description: "case, Esegui branch diversi in base al valore di un'espressione."
categories: "common"
---
> Maggiori informazioni: <https://manned.org/case>.

- Esegui il match di una variabile su diverse stringhe per decidere che comando eseguire:

```bash
case $metrica in parole) wc -w README; ;; linee) wc -l README; ;; esac
```

- Combina pattern con |, utilizzando * come pattern di fallback:

```bash
case $metrica in [pP]|parole) wc -w README; ;; [lL]|linee) wc -l README; ;; *) echo "cosa?"; ;; esac
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | case: add link | 2021-04-18T16:33:27 | [4d87a4e1a562](https://github.com/tldr-pages/tldr/commit/4d87a4e1a562f8aa1581c21aa263994d3c5078fa)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | case: add Italian translation. | 2019-01-28T19:10:19 | [2b628e375154](https://github.com/tldr-pages/tldr/commit/2b628e375154809e33863fff4c745d25b2078a75)

