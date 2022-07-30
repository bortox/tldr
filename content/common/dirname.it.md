---
author: ['Dario Vladović', 'Marco Bonelli', 'marchersimon']
date: 1617292466
title: "dirname"
description: "dirname, Determina la directory genitore di un determinato file o percorso."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/dirname>.

- Calcola la directory genitore di un dato percorso:

```bash
dirname percorso/a/file_o_directory
```

- Calcola la directory genitore di più percorsi:

```bash
dirname percorso/a/file_a percorso/a/directory_b
```

- Delimita l'output con caratteri NUL invece di newline (utile in combinazione con `xargs`):

```bash
dirname --zero percorso/a/directory_a percorso/a/file_b
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | dirname: add link (#5604) | 2021-03-30T15:55:16 | [016c255e46ff](https://github.com/tldr-pages/tldr/commit/016c255e46ff9a07e2a8bf279a039cb6cfddfdb8)
[Marco Bonelli](mailto:marco@mebeim.net) | dirname: add Italian translation. | 2019-07-21T01:59:28 | [d311993f0eff](https://github.com/tldr-pages/tldr/commit/d311993f0eff2e4a15123b36898dba8c132efed0)

