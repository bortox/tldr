---
author: ['Marco Bonelli', 'Schneider', 'marchersimon']
date: 1626166788
title: "astyle, TLDR Pages"
description: "astyle, Indentatore, formattatore e beautifier di codice sorgente per i linguaggi C, C++, C# e Java."
categories: "common"
---
> Quando eseguito, una copia del file originale è creata con l'estensione ".orig" aggiunta come suffisso.

> Maggiori informazioni: <http://astyle.sourceforge.net/>.

- Applica lo stile di default di 4 spazi per livello di indentazione e nessun cambiamento alla formattazione:

```bash
astyle file_sorgente
```

- Applica lo stile Java con parentesi graffe aperte sulla stessa riga (attached braces):

```bash
astyle --style=java percorso/al/file
```

- Applica lo stile allman per parantesi graffe su linee separate (broken braces):

```bash
astyle --style=allman percorso/al/file
```

- Applica un'indentazione personalizzata utilizzando spazi. Scegli tra 2 e 20 spazi:

```bash
astyle --indent=spaces=numero_spazi percorso/al/file
```

- Applica un'indentazione personalizzata utilizzando tab. Scegli tra 2 e 20 tab:

```bash
astyle --indent=tab=numero_tab percorso/al/file
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace `java` with `Java` and `c++` with `C++` (#6224) | 2021-07-13T10:59:48 | [b615ea1e3495](https://github.com/tldr-pages/tldr/commit/b615ea1e34951c855e72470b73522ed0e0963d87)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | astyle: reword description (#3150) | 2019-06-29T19:23:51 | [d496b0c18f45](https://github.com/tldr-pages/tldr/commit/d496b0c18f450c4504c0c643ade531e79fdd1484)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\astyle.md:add homepage | 2019-05-14T19:40:23 | [70a3f6f05567](https://github.com/tldr-pages/tldr/commit/70a3f6f055673699c3b7576a2e83bfe90e06dcc0)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | astyle: add Italian translation. | 2019-01-28T19:10:19 | [d83e191e8a86](https://github.com/tldr-pages/tldr/commit/d83e191e8a8652e91e1d2879dafa57b72c0b0c46)

