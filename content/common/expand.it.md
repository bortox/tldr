---
author: ['Marco Bonelli', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "expand, TLDR Pages"
description: "expand, Converti caratteri tab in spazi."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/expand>.

- Converti tab in un file in spazi, scrivendo su standard output:

```bash
expand file
```

- Converti i tab in spazi, leggendo da standard input:

```bash
expand
```

- Non convertire i tab dopo caratteri di spaziatura:

```bash
expand -i file
```

- Sostituisci i tab con un determinato numeroo di spazi, non 8 (default):

```bash
expand -t=numero_spazi file
```

- Utilizza una lista separata da virgole di posizioni esplicite di tab:

```bash
expand -t=1,4,6
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | expand: add more information link (#5577) | 2021-03-30T15:29:04 | [6125eef67926](https://github.com/tldr-pages/tldr/commit/6125eef6792600c63c4618c85296b83e4f724320)
[Marco Bonelli](mailto:marco@mebeim.net) | expand: add Italian translation. | 2019-10-05T15:25:51 | [f928d3f41c9d](https://github.com/tldr-pages/tldr/commit/f928d3f41c9d7ce19442dc3894651c3ec8c4815a)

