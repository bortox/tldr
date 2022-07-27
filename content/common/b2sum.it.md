---
author: ['Marco Bonelli', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "b2sum, TLDR Pages"
description: "b2sum, Calcola checksum BLAKE2."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/b2sum>.

- Calcola il checksum BLAKE2 per un file:

```bash
b2sum file1
```

- Calcola checksum BLAKE2 per più file:

```bash
b2sum file1 file2
```

- Leggi un file di checksum BLAKE2 e nomi di file e verifica che tutti i file abbiano lo stesso checksum:

```bash
b2sum -c elenco_checksum.b2
```

- Calcola il checksum BLAKE2 da standard input:

```bash
comando | b2sum
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | b2sum: change more information link (#5563) | 2021-03-30T12:25:10 | [572bb893c6d2](https://github.com/tldr-pages/tldr/commit/572bb893c6d23a07c13c09b6dd61a954a1950381)
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | b2sum: add Italian translation. | 2019-01-28T19:10:19 | [9e668954bcf8](https://github.com/tldr-pages/tldr/commit/9e668954bcf81c436a8722844bc1992b06247541)

