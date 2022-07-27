---
author: ['Marco Bonelli', 'Schneider', 'bl-ue']
date: 1621541621
title: "calibredb, TLDR Pages"
description: "calibredb, Strumentoi per gestire il tuo database di e-book."
categories: "common"
---
> Parte del manager di e-book Calibre.

> Maggiori informazioni: <https://manual.calibre-ebook.com/generated/en/calibredb.html>.

- Elenca gli e-book nella libreria con informazioni aggiuntive:

```bash
calibredb list
```

- Cerca tra gli e-book mostrando informazioni aggiuntive:

```bash
calibredb list --search termine_di_ricerca
```

- Cerca mostrando solamente gli ID degli e-book:

```bash
calibredb search termine_di_ricerca
```

- Aggiungi uno o più e-book alla libreria:

```bash
calibredb add file1 file2 …
```

- Rimuovi uno o più e-book dalla libreria. Sono necessari gli ID (vedi sopra):

```bash
calibredb remove id1 id2 …
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\calibredb.md: add homepage | 2019-05-14T19:40:23 | [043c9fdad712](https://github.com/tldr-pages/tldr/commit/043c9fdad712a8ab3844b6b8493e21c511558e9a)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | calibredb: add Italian translation. | 2019-01-28T19:10:19 | [1921f06413bd](https://github.com/tldr-pages/tldr/commit/1921f06413bd9500f750ab458dab7fe944afc64b)

