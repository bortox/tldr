---
author: ['Schneider', 'Marco Bonelli', 'marchersimon']
date: 1633112881
title: "7za"
description: "7za, Archiviatore di file con alto fattore di compressione."
categories: "common"
---
> Versione standalone di `7z` con supporto a meno tipi di archivi.

> Maggiori informazioni: <https://www.7-zip.org>.

- Archivia un file o una directory:

```bash
7za a archivio.7z percorso/a/file_o_directory
```

- Estrai un archivio mantenendo la gerarchia delle cartelle:

```bash
7za x archivio.7z
```

- Archivia utilizzando uno specifico tipo di archivio:

```bash
7za a -t zip|gzip|bzip2|tar archivio.7z percorso/a/file_o_directory
```

- Elenca i tipi di archivio supportati:

```bash
7za i
```

- Elenca i contenuti in un archivio:

```bash
7za l archivio
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\7za.md: add homepage | 2019-05-14T19:40:23 | [306a668e227b](https://github.com/tldr-pages/tldr/commit/306a668e227bdc5e31118774d1f2131568e57b47)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: add missing `or_directory` where needed. This commit adds the missing `_or_directory` to any example which is specifying an [...] | 2019-02-08T20:43:24 | [f79f6011e0f2](https://github.com/tldr-pages/tldr/commit/f79f6011e0f298311848b5f38d66c309d4b92665)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | 7z, 7za, svn: remove unneeded ellipsis. svn: remove unneeded ellipsis. | 2019-02-03T04:27:37 | [24ff2872510f](https://github.com/tldr-pages/tldr/commit/24ff2872510f7bfac1e82fc333d8b928a8c50a0e)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: add italian translations (#2692) Translated 13 pages into italian: 7z 7za 7zr ab abduco ack adb ag airpaste alias [...] | 2019-01-11T01:34:17 | [1286509fe557](https://github.com/tldr-pages/tldr/commit/1286509fe557aaa701a1ebe07ce0c5c0b7ef6959)

