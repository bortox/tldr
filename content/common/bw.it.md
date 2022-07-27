---
author: ['Marco Bonelli', 'Schneider']
date: 1559564381
title: "bw, TLDR Pages"
description: "bw, CLI per accedere e gestire vault Bitwarden."
categories: "common"
---
> Maggiori informazioni: <https://help.bitwarden.com/article/cli/>.

- Esegui il login ad un account Bitwarden:

```bash
bw login
```

- Esegui il logout da un account Bitwarden:

```bash
bw logout
```

- Cerca e mostra oggetti in un vault Bitwarden:

```bash
bw list items --search github
```

- Mostra un particolare oggetto contenuto in un vault Bitwarden:

```bash
bw get item github
```

- Crea una cartella in un vault bitwarden:

```bash
echo -n '{"name":"Nome cartella"}' | base64 | bw create folder
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\bw.md:add homepage | 2019-05-14T19:40:23 | [83da18878fd7](https://github.com/tldr-pages/tldr/commit/83da18878fd74e65f519ca38ba872103ba3a052d)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | bw: add Italian translation. | 2019-01-28T19:10:19 | [51de02ee3d89](https://github.com/tldr-pages/tldr/commit/51de02ee3d893493c7f2eeeef156aac103e836c0)

